# Swift-Ruby
## Attempting to bring some of the nice features from Swift to Ruby.

---

## Accepting pull requests! Ideally with specs.

---
I created this project mostly as a stub, with only one implementation - hoping you will step in and create additional implementations for features you like in swift.

Also I'm not tied to the naming, structure, testing framework, or anything. If anyone is willing to help out, you will get a lot of say :)
### 1. Question mark for method calls:

(Swift's Optionals: http://stackoverflow.com/questions/24057171/what-the-meaning-of-question-mark-in-swift)

I believe Swift implements this for other things than just method calls, this is just the first thing I tackled:

```swift
employee.transfer?(2)
```

This is like ruby's ".try()" but with the following syntax:

```ruby
e = Employee.new
e.transfer?(1)
```

The above should not fail if the method doesn't exist.

spec: [spec/question_mark_for_method_calls_spec.rb](spec/question_mark_for_method_calls_spec.rb)
code: [question_mark_for_method_calls.rb](question_mark_for_method_calls.rb)

