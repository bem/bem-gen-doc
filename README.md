BEM-GEN-DOC
===========

**bem-gen-doc** is a documentation generator which converts documentation of BEM-libraries' items
(blocks, elements or modifiers) into HTML website.

_This project is still under development_

Usage
-----

    › git clone git://github.com/bem/bem-gen-doc.git
    › cd bem-gen-doc
    › npm install

The simple usage example could be found in the `example` directory.

To build `example` documentation site follow this steps:

    › bem make -r example vendor

This will install all dependancies for library.

Now lets build our example:

    › bem make -r example/ site

The build process should start. It will take a few moments. When it's done, we could
start our develepor server and look at result:

    › bem server

Server will start on port 8080, so you could point your browser to
`http://localhost:8080/release/index/index.html` page.

**NOTE**

`bem` should be in your `PATH` environment variable. You could do this by adding this line to your user's
`.profile` config:

    exports PATH=./node_modules/.bin:$PATH

---

BEM is abbreviation for Block-Element-Modifier. It's a way to write code which is easy to support and develop.

For more info about BEM metodology see [bem.info](http://bem.info/).

