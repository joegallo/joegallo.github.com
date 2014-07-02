`bundle exec jekyll serve --watch`

AND

`bundle exec irb`

THEN

```ruby
require 'pygments'
Pygments.styles
File.open('includes/pygments.css', 'w') { |f| f.puts Pygments.css(".highlight", :style => 'autumn') }
```

(more or less from https://github.com/tmm1/pygments.rb)
