# What do before and after filters do in Sinatra?

## What are before filters?
> Before filters are evaluated before each request within the same context as the routes will be and can modify the request and response.
```ruby
class Url < ActiveRecord::Base
  before do
    puts "do something(App before filter) + more..."
  end
end
```

## What are after filters?
> After filters are evaluated after each request within the same context as the routes will be and can also modify the request and response.
```ruby
after do
  puts 'after called'
end
```


- Step 1: Create filter.rb and add before filters.
- Step 2: bundle exec shotgun filter.rb
- Step 3: Browse to http://localhost:9393/ and Browser output will be the result of your Before call.
- Step 4: Add after filter.
- Step 5: Reload the browser. See both Before called and after called outputs in the server page.

### Available Callbacks
1. Creating an Object
- before_validation
- after_validation
- before_save
- around_save
- before_create
- around_create
- after_create
- after_save
- after_commit/after_rollback
2. Updating an Object
- before_validation
- after_validation
- before_save
- around_save
- before_update
- around_update
- after_update
- after_save
- after_commit/after_rollback
3. Destroying an Object
- before_destroy
- around_destroy
- after_destroy
- after_commit/after_rollback

