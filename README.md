octo-iframe
===========

a jekyll/octopress plugin for embedding iframes

##How to Use

Copy `iframe.rb` file into your `octopress/plugins` for octopress or `{jekyll_blog_root}/_plugins` directory for jekyll.

Then add the following code into any post, substituting the value for class, src, width and height that you want:

```
{% iframe [class] [src] [width] [height] %}
```

###Sample Usage

Input:

```
{% iframe cmd http://showterm.io/67772b674551d4a236e0a 640 480 %}
```

Output:

``` 
<iframe class="cmd" src="http://showterm.io/67772b674551d4a236e0a" width="640" height="480">
```


##License

The MIT License (MIT) Copyright (c)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.