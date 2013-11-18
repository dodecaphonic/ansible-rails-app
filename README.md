# A small Rails/Sinatra/rack-ready playbook for Ansible

It installs:

- nginx
- Puma (jungle)
- Ruby 2.0.0-p247
- PostgreSQL
- memcached
- Redis (for Sidekiq)

Change the app name, host and deploy directory in <code>vars/defaults.yml</code>.

To run:

    $ ansible-playbook ruby-webapp.yml
