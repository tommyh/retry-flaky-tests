# retry-flaky-tests
Bash command to retry a flaky test until it fails.  When you have a test which fails intermittenly, sometimes you just want to run the test in a loop until it fails.

## Usage

```bash
./loop.sh rspec spec/my_flaky_test.rb
```
