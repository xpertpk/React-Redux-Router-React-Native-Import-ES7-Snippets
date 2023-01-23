# React/Redux/Router/React-Native/Import & ES7 Snippets

## Snippets info
React, Redux, Router, and Import are all commonly used in React applications to handle different aspects of the application's functionality and structure. Here are some benefits of using snippets for these technologies:

* Increased productivity: Snippets can help you write code faster and more efficiently, allowing you to focus on the logic of your application rather than the syntax of the different libraries and frameworks.

* Consistency: Using snippets can help ensure that your code is consistent and follows best practices, making it easier to maintain and understand.

* Reduced errors: Snippets can help reduce the number of errors in your code, as they are pre-written and tested code patterns.

* Learning aid: Snippets can be a useful tool for learning these technologies, as they can help you understand how different parts of React, Redux, Router, and Import work and how they can be used in your application.

* Community support: Many popular code editors like Visual Studio Code, have a large community of developers who contribute and share their own snippets, so you can find the snippet that best suits your needs.

* Customization: You can also customize and modify the snippets to fit your specific requirements and development style.

Overall, using snippets for React, Redux, Router and Import can be a valuable tool for developers working with these technologies, helping them write code faster, more efficiently and with fewer errors.


## Supported languages (file extensions)

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript (.jsx)


## Basic Methods

### import

| Trigger  | Content |
| -------: | ------- |
| `imr`    | `import React from 'react'` |
| `imrc`   | `import React, { Component } from 'react'` |
| `imd`    | `import { render } from 'react-dom'` |
| `impt`   | `import PropTypes from 'prop-types'` |
| `imc`    | `import ${1:componentName} from './Components/${1:componentName}'` |
| `imconnect`    | `import { connect } from 'react-redux'` |
| `improvider`    | `import { Provider } from 'react-redux'` |
| `imcreateSelector`    | `import { createSelector } from 'reselect'` |
| `imrr`   | `import { BrowserRouter, Route } from 'react-router-dom'` |
| `imnl`    | `import { NavLink } from 'react-router-dom'` |
| `imwr`    | `import { withRouter } from 'react-router-dom'` |

### React

| Trigger  | Content |
| -------: | ------- |
| `rcc→`   | class component skeleton |
| `rccp→`  | class component skeleton with prop types after the class |
| `rcjc→`  | class component skeleton without import and default export lines |
| `rcfc→`  | class component skeleton that contains all the lifecycle methods |
| `rsc→`   | stateless component skeleton |
| `rscp→`  | stateless component with prop types skeleton |
| `rpt→`   | empty propTypes declaration |
| `spt→`   | `static propTypes = {}` |
| `sdp→`   | `static defaultProps = {}` |
| `con→`   | class default constructor with props|
| `conc→`  | class default constructor with props and context |
| `est→`   | empty state object |
| `st→`    | Creates empty state object with ES7 synTax |
| `cwm→`   | `componentWillMount` method |
| `cdm→`   | `componentDidMount` method |
| `cwr→`   | `componentWillReceiveProps` method |
| `scu→`   | `shouldComponentUpdate` method |
| `cwup→`  | `componentWillUpdate` method |
| `cdup→`  | `componentDidUpdate` method |
| `cwun→`  | `componentWillUnmount` method |
| `cdc→`   | `componentDidCatch` method |
| `ren→`   | `render` method |
| `sst→`   | `this.setState` with object as parameter |
| `ssf→`   | `this.setState` with function as parameter |
| `props→` | `this.props` |
| `state→` | `this.state` |
| `bnd→`   | `binds the this of method inside the constructor` |
| `pta→`   | `PropTypes.array,` |
| `ptar→`  | `PropTypes.array.isRequired,` |
| `ptb→`   | `PropTypes.bool,` |
| `ptbr→`  | `PropTypes.bool.isRequired,` |
| `ptf→`   | `PropTypes.func,` |
| `ptfr→`  | `PropTypes.func.isRequired,` |
| `ptn→`   | `PropTypes.number,` |
| `ptnr→`  | `PropTypes.number.isRequired,` |
| `pto→`   | `PropTypes.object.,` |
| `ptor→`  | `PropTypes.object.isRequired,` |
| `pts→`   | `PropTypes.string,` |
| `ptsr→`  | `PropTypes.string.isRequired,` |
| `ptnd→`  | `PropTypes.node,` |
| `ptndr→` | `PropTypes.node.isRequired,` |
| `ptel→`  | `PropTypes.element,` |
| `ptelr→` | `PropTypes.element.isRequired,` |
| `pti→`   | `PropTypes.instanceOf(ClassName),` |
| `ptir→`  | `PropTypes.instanceOf(ClassName).isRequired,` |
| `pte→`   | `PropTypes.oneOf(['News', 'Photos']),` |
| `pter→`  | `PropTypes.oneOf(['News', 'Photos']).isRequired,` |
| `ptet→`  | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]),` |
| `ptetr→` | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]).isRequired,` |
| `ptao→`  | `PropTypes.arrayOf(PropTypes.number),` |
| `ptaor→` | `PropTypes.arrayOf(PropTypes.number).isRequired,` |
| `ptoo→`  | `PropTypes.objectOf(PropTypes.number),` |
| `ptoor→` | `PropTypes.objectOf(PropTypes.number).isRequired,` |
| `ptsh→`  | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}),` |
| `ptshr→` | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}).isRequired,` |

### Redux

| Trigger  | Content |
| -------: | ------- |
| `rat`  | Redux constant(actionTypes) |
| `rac`  | Redux actionCreator |
| `reducer`  | Redux reducer |
| `store`  | Redux store |
| `selector`  | Redux selector |

### react-redux

| Trigger  | Content |
| -------: | ------- |
| `imconnect`    | `import { connect } from 'react-redux'` |
| `improvider`    | `import { Provider } from 'react-redux'` |
| `provider`  | react-redux Provider Container |
| `mstp`  | mapStateToProps |
| `mdtp`  | mapDispatchToProps |
| `connect`  | react-redux connect React Component |
| `container`  | Redux container |

### react-router

| Trigger  | Content |
| -------: | ------- |
| `imrr`   | `import { BrowserRouter as Router, Route } from 'react-router-dom'` |
| `imnl`    | `import { NavLink } from 'react-router-dom'` |
| `imwr`    | `import { withRouter } from 'react-router'` |
| `router`  | react-router Router template |
| `route`  | react-router  Route component |
| `navlink`  | react-router  NavLink component |


## Contributors

* [XpertPK](https://github.com/xpertpk)


## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension.


## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of React/Redux/Router/React-Native/Import & ES7 Snippets

---

## Publisher

###### Mern Stack Developer - Shahbaz Mughal
@xpertpk

My Passion and Love:

**Hostings House & Mumara**.

![React Snippets Logo](./images/react.png)

**Enjoy!**
