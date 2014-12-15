testing-with-rspec
==================


##### RSPEC

- Popular Ruby testing framework
- Thriving community
- Less Ruby-like, natural syntax
- Well-formated output

##### Behavior-Driven Dev
- Describe your application's behavior
  - Can be done with other frameworks
  - BDD is not required
  - But encouraged by the RSpec syntax
  - And RSpec makes it elegant and readable
  
##### Expectations

```ruby
describe Zombie do
it "is named Ash" do
    zombie = Zombie.new
    zombie.name.should == 'Ash'
    end
end
```

- This is how you 'assert' in RSpec
- Assertions are called 'expectations'
- They read more like plain English
