require 'rake'
require 'rake/task'
require 'serve'

namespace :StrapOn do
  desc "Preview the site for development"
	task :start do
		puts " "
		puts " "
		puts "StrapOn starting....................."
		puts " "
		puts " "
		sh "serve"
		puts " "
		puts " "
		puts "StrapOn shutting down................"
		puts "Generating static version of site in: ./_site/ ..."
		puts " "
		puts " "
		sh "serve export . _site/"
	end

  desc "Export the static site"
	task :export do
		puts " "
		puts " "
		puts "StrapOn exporting static site....................."
		puts " "
		puts " "
		puts "Generating static version of site in: ./_site/ ..."
		sh "serve export . _site/"
	end
end
		