# Print a simple progress counter on console using ruby

Imagine if you want to print a simple progress counter in the console output, at the same line.
```ruby
100.times { |i| print "#{i}%"; sleep 0.1; print "\r" }
```

The magic is with the carriage-return character `\r`. 