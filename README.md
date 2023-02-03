# RSpec Exercises 3

Download the project skeleton below and upload your work when you are finished.

See the "Practice Instructions" reading under W1D1->PROJECTS in the sidebar if
you need help downloading, opening, or uploading the project.

This practice uses RSpec tests to guide and check your work. Run `bundle
install` in your terminal to set up the project. Then run `bundle exec rspec`.
The tests should all fail. Your job is to implement the methods outlined by the
RSpec output. Do this in the corresponding __lib/__ files:

* Part 1 (__lib/part_1.rb__)
  * `is_prime?`
  * `nth_prime`
  * `prime_range`
* Part 2 (__lib/part_2.rb__)
  * `element_count`
  * `char_replace!`
  * `product_inject`

Work until all the specs are green/passing. Look at the __spec/__ files to get
additional clarity or hints on how to satisfy specific specs.

You may find the following RSpec commands useful:

To run all the specs: `bundle exec rspec`  
To run all Part 1 specs: `bundle exec rspec spec/part_1_spec.rb`  
To run all Part 2 specs: `bundle exec rspec spec/part_2_spec.rb`  
To run the spec that begins, e.g., on line 5: `bundle exec rspec spec/part_1_spec.rb:5`