# How to write markdown

### Hunter T. Chapman

This is a sample of how you might document a particular topic using markdown. It doesn't have to be professional grade, but I want you to get used to writing and conveying topics in this manner just as much as I want you to get comfortable in conveying logic in a conversational setting. :-)

### Markdown Overview

Markdown is crazy important because as developers it is generally the first thing we read about given piece of software when we come to the app in GitHub.

Use markdown to document how to do things. Writing quality documentation is part of becoming a successful web developer. You should get to the point straight away and use illustrations or links to backup that info.

Markdown can convey everything from technical instructions to what people are having for lunch.

### Syntax Overview

Syntax in markdown is pretty straightforward. Here are a few examples:

To create a code encapsulation block use three backticks "```" to open and close the block. These can be single or multiline and can even be syntax highlighted if you declare the language you are using after the first set of backticks. So I could put something like this into my file.
```ruby
class Thing < Stuff
  def initialize(args = {})
    @foo = args[:foo]
    @bar = args[:bar]
  end

  def do_things
    puts "ALL THE THINGS!!!"
  end
end
```

To create a link use
```
[name of link](actual link)
```

To insert an image use
```
![Alt text](/path/to/img.jpg)
```

To create a unordered list use a dash at the beginning of the line.
```
-
```

### Links

- [Markdown Syntax Guide](https://daringfireball.net/projects/markdown/syntax)
- [Markdown CheatSheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
