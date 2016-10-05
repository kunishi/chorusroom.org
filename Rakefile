require 'html-proofer'

task :test do
  sh "bundle exec jekyll build --destination ./_site/chorusroom.org"
  HTMLProofer.check_directory("./_site", {:allow_hash_href => true, :empty_alt_ignore => true}).run
end
