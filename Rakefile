# # #
# Build tasks

require 'middleman-gh-pages'

desc 'Deploy to ruby.style'
task :deploy => :publish do
  sh "git checkout gh-pages && git pull origin gh-pages && git push production gh-pages:master -f && git checkout -"
end

