require "bundler/gem_tasks"
require "rspec/core/rake_task"
require "rubocop/rake_task"

task default: [:spec, :rubocop]

RSpec::Core::RakeTask.new(:spec) do |t|
  t.verbose = false
  t.ruby_opts = "-w"
end

RuboCop::RakeTask.new(:rubocop)
