# RAILS ACTIVE STORAGE OVERVIEW
This project shows Rails Active Storage general usage, as presented in the [Rails Active Storage guide](https://guides.rubyonrails.org/active_storage_overview.html).

## Project Overview
This project mocks a _Customer_ management service. It adds an _avatar_ to introduce Active Storage usage.

One can follow along the entire process by checking out each commit in this project.

## Running the Project
First off, ensure you have the prerequisites to run a rails application, [which are](https://guides.rubyonrails.org/getting_started.html#creating-a-new-rails-project-installing-rails):
- Ruby
- Rails
- SQLite

Then, clone this repository: `git clone https://github.com/gabrielcostasilva/rails-storage.git`

Next, update the database by running **in the project folder**: `bin/rails db:migrate`

Finally, start the server with: `bin/rails server`

> All these commands must be run from your console in the project folder.

Access the application at [http://localhost:3000/customers](http://localhost:3000/customers), create a new customer, attaching an avatar in the process.

