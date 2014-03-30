source 'https://rubygems.org'

group :development do
  gem 'rake', '~> 10.2.0'
end

group :lint do
  gem 'foodcritic', '~> 3.0.3'
  gem 'rubocop', '~> 0.19.1'
end

group :unit do
  gem 'berkshelf', github: 'berkshelf/berkshelf'
  gem 'chefspec', '~> 3.4.0'
end

group :kitchen_common do
  gem 'test-kitchen', '~> 1.2.1'
end

group :kitchen_vagrant do
  gem 'vagrant', github: 'mitchellh/vagrant', tag: 'v1.4.3'
  gem 'vagrant-berkshelf', github: 'berkshelf/vagrant-berkshelf'
  gem "vagrant-omnibus", github: 'schisamo/vagrant-omnibus', tag: "v1.1.2"
  gem 'kitchen-vagrant', '~> 0.14.0'
end

group :kitchen_cloud do
  gem 'kitchen-ec2', github: 'americanhonors/kitchen-ec2', branch: 'feature/public_ip_address'
  gem 'unf', '~> 0.1.3'
end
