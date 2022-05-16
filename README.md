# managePackages-LearnNPM

# Backend Development & APIs

## Managing Packages with NPM

The package.json file is the center of any Node.js project or npm package. It stores information about your project, similar to how the <head> section of an HTML document describes the content of a webpage. It consists of a single JSON object where information is stored in key-value pairs. There are only two required fields; "name" and "version", but it’s good practice to provide additional information about your project that could be useful to future users or maintainers. <br>

This document (package.json) is all you need to know about what's required in your package.json file. It must be actual JSON, not just a JavaScript object literal.<br>

A lot of the behavior described in this document is affected by the config settings described in config.
Remember that you’re writing JSON, so all field names must use double-quotes (") and be separated with a comma (,).<br>

Package.json tend to include the following: 
    name
    version
    description
    keywords
    homepage
    bugs
    license
    people fields: authors, contributors
    funding
    optional: files
    main
    browser
    bin
    man
    directories
    repositories
    scripts
    config
    dependencies
    engines
    os
    ...

Node.js files contain tasks that will be executed on certain events
A typical event is someone trying to access a port on the server
Node.js files must be initiated on the server before having any effect
Node.js files have extension ".js"