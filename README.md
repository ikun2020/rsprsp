# rsp


### How do I put line numbers in my code?

You can use the `linenums` class to turn on line numbering.  If your code
doesn't start at line number `1`, you can add a colon and a line number to the
end of that class as in `linenums:52`. For example:

```HTML
<pre class="prettyprint linenums:4"
>// This is line 4.
foo();
bar();
baz();
boo();
far();
faz();
</pre>
