require 'rspec/core/rake_task'
require 'rubocop/rake_task'
require 'foodcritic'

RuboCop::RakeTask.new
FoodCritic::Rake::LintTask.new
RSpec::Core::RakeTask.new(:rspec)

task default: %i[rubocop foodcritic]