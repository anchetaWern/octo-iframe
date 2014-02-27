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