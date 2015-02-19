##Introduction

This repository contains [ReactJS](http://facebook.github.io/react/) Live Templates to use with [JetBrains WebStorm](http://www.jetbrains.com/webstorm/). These templates are based off of the [sublime-react](https://github.com/reactjs/sublime-react) snippets provided by the React team.

Live Templates are a set of abbreviations that expand in to 'code snippets' for common tasks such as creating variables and functions. These abbreviations significantly speed up development and reduce coding errors.

##Installation

### WebStorm
First, find the directory WebStorm uses to store its settings. See [this post](https://intellij-support.jetbrains.com/entries/23358108) for more information on where to find the correct path on your operating system. Once you've found the correct path, find the 'templates' directory and drop in the XML file. For more information on using Live Templates in WebStorm, [click here](https://www.jetbrains.com/webstorm/help/live-templates-2.html).

##Available Snippets

```
    cdm→  componentDidMount: fn() { ... }

   cdup→  componentDidUpdate: fn(pp, ps) { ... }

     cs→  var cx = React.addons.classSet;

    cwm→  componentWillMount: fn() { ... }

    cwr→  componentWillReceiveProps: fn(np) { ... }

    cwu→  componentWillUpdate: fn(np, ns) { ... }

   cwun→  componentWillUnmount: fn() { ... }

     cx→  cx({ ... })

    fup→  forceUpdate(...)

    gdp→  getDefaultProps: fn() { return {...} }

    gis→  getInitialState: fn() { return {...} }

    ism→  isMounted()

  props→  this.props.

     pt→  propTypes { ... }

    rcc→  component skeleton

   refs→  this.refs.

    ren→  render: fn() { return ... }

    scu→  shouldComponentUpdate: fn(np, ns) { ... }

    sst→  this.setState({ ... })

  state→  this.state.

```

##Credits
* [sublime-react](https://github.com/reactjs/sublime-react) for initial creation of the Sublime React snippets these Live Templates were based on
