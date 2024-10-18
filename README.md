# RAILS ACTIVE STORAGE OVERVIEW
This project shows Rails Active Storage general usage, as presented in the [Rails Active Storage guide](https://guides.rubyonrails.org/active_storage_overview.html).

## Project Overview
This project mocks a _Customer_ management service. It adds an _avatar_ to introduce Active Storage usage.

One can follow along the entire process by checking out each commit in this project.

### Configuring for AWS S3
Extending the project to using AWS S3 as default storage service required:

1. [Adding S3 GEM](https://github.com/gabrielcostasilva/rails-storage/commit/a5164f458b67339ab58c81553b83254af22169a0)
2. [Setting AWS credentials and bucket name](https://github.com/gabrielcostasilva/rails-storage/commit/b55548bc171b66d95feed3d513f718eabee3825f)
3. [Switching default storage to S3](https://github.com/gabrielcostasilva/rails-storage/commit/b95c2543dc13b317636e5b23ff8bad099ca62d19)

But, previously, you need to create:
1. S3 Bucket
2. AIM user with permission to read/write the bucket

(and an AWS account, obviously ...)


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

