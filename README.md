# vzhz.github.io
Personal portfolio page, written from scratch.  Practicing controlling element placement with my mind (CSS).

## To test your templating locally
This site is now being templated using [Jinja2](http://jinja.pocoo.org/docs/2.10/). If you would like to clone and further adjust the template, you can use static website generator to test that your templating is including all parts of the site.

To test with a static site generator:
- Ensure that the file <code>compiler.py</code> (from [this blog post](oltaCXH7HjJFA8jPHRqDXT0ImaKI)) is in your primary folder and that your HTML files are in a <code>src/</code> folder and your assets (css, js, images, etc.) in a <code>static</code> subdirectory. Your generated HTML will appear in a <code>dist</code> directory once run.
- Start a [local Python server](https://docs.python.org/2/library/simplehttpserver.html) with <code>python -m SimpleHTTPServer 8000</code> while in the project folder.
- Open a browser to <code>http://localhost:8000/</code>. Nothing yet!
- From a new terminal tab, navigate to the project's primary directory and run <code>python compiler.py</code>
- Check that the result shown in the browser is what you expect. Cheer and abstract on if it is!
