require 'html/proofer'

task :test do
  sh "bundle exec jekyll build"
  HTML::Proofer.new("./_site", validate_html: true, favicon: true).run
end

task :default => [:test]
