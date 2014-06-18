Active Record Lite

As magical as ActiveRecord may be, it's important to understand how it works and how ActiveRecord acts as an ORM between Rails and your database. What better way to learn the logic behind the scenes than recreating a light version of ActiveRecord itself?

Active Record Lite heavily uses Ruby metaprogramming and raw SQL statements to recreate the methods that ActiveRecord provides for us in Rails.