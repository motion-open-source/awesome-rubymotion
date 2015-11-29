desc 'toolbox2md'
task :toolbox2md do
  require 'open-uri'
  require 'json'
  require 'pp'

  request_uri = 'https://raw.githubusercontent.com/clayallsopp/motion-toolbox.com/master/data.json'
  request_query = ''
  url = "#{request_uri}#{request_query}"

  buffer = open(url).read

  result = JSON.parse(buffer)
  #PP.pp result
  result['categories'].each do |cat|
    cat['wrappers'].each do | w |
      print "* [#{w['name']}](#{w['url']}) - #{w['description']}\n"
    end
  end

  puts "Finished!\n\n"
end
