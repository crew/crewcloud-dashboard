# OpenStack Dashboard

An OpenStack Dashboard for the CCIS Open Cloud (AKA CrewCloud)

![It makes OpenStack clean and awesome](http://i42.tinypic.com/1hp3q0.gif)

## Getting Started 

It's A Rails App, so just

```
git clone https://github.com/crew/crewcloud-dashboard
cd crewcloud-dashboard
bundle install
rails s
open http://localhost:3000
```

We Recommend using Sublime Text 3 or RubyMine when developing

## Project Specs

### Goals

* Develop a Dashboard that successfully wraps OpenStack and provides a much more intuative user interface than Horizon.  See [DigitalOcean](https://cloud.digitalocean.com)

* Add Functionality to transfer ownership of Instances by a student to in essence "Submit" a VM to a teacher for grading
* Add Functionality to allow Students to quickly and easily spin up prebuilt servers for
  * Web App Server (Apache)
  * Load Balancer (NGINX)
  * DNS (Bind9/named)
  * LDAP Authentication
  * PuppetMaster (Foreman)
* Allow Students to select from Security Group Templates that are predefined for certain applications
* Fully Responsive Design with optimised mobile functionality for Starting, Stopping, and Rebooting Instances

### Suggestions

Bootstrap for UI basics.  Also some free themes at http://bootstrapzero.com/

## Testing

### Run All Tests

```
rake test
```

### Run a single test

For a single test where 25 is the line of the spec file where the `it` definition lives:

```
bundle exec rspec spec/my_spec.rb:25
```

## Documentation
Managed On [Trello](https://trello.com/b/WJ02ddqh)
Visit the [wiki](https://github.com/crew/crewcloud-dashboard/wiki)
