# Jungle

Jungle is a mini e-commerce application built with Rails 4.2 for purposes of teaching Rails by example. This project was a simulation of the real world e-commerce website where I learned a new language, ecosystem and framework.

## Added Feature
- Sold-out badge
- Added categories for products
- Bug fixes on user interface and missing admin security
- User authentication; hashed password using bcrypt
- Allowed only admins to add products and categories

## Tested 
- RSpec
- Capybara
- Poltergeist
- Database_cleaner

## Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rake db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

* Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
* PostgreSQL 9.x
* Stripe

## Final Product

### Home Page
!["screenshot of homepage"](/docs/jungle-homepage.jpg)

### Admin Categories
!["screenshot of admin categories"](/docs/admin-categories.jpg)

### Admin Products
!["screenshot of admin products"](/docs/admin-products.jpg)

### My Cart
!["screenshot of cart"](/docs/my-cart.jpg)

### Signups
!["screenshot of signups"](/docs/signup-page.jpg)
