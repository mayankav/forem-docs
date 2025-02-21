---
sidebar_position: 2
---

# Integration Tests

An integration test is a test that measures the interaction of multiple systems
or parts of your application.

An integration test may seem similar to an [acceptance
test](acceptance-tests.md). The main difference is that an acceptance test
is from the perspective of the end-user, while an integration test is from the
perspective of the developer.

Integration tests can be found in the directory `spec/requests`.

You can run all integration tests with:

```shell
bundle exec rspec spec/requests
```

To run an individual file you can use:

```shell
bundle exec rspec spec/requests/stories_show_spec.rb
```

To run a specific test case you can use:

```shell
bundle exec rspec spec/requests/stories_show_spec.rb:10
```

where `10` is the line number of the test case that you want to execute.
