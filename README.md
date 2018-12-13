# Code Snippets

###### Curated list of Javascript, React code snippets for faster coding.

#### React Functional / State less component

```javascript
import React from "react";
import PropTypes from "prop-types";

const componentName = props => {
  return <div />;
};

componentName.propTypes = {};

componentName.defaultProps = {};

export default componentName;
```

### Code Snippet - React Functional / State less component

```
"React Functional Component": {
    "prefix": "RFC",
    "body": [
      "import React from 'react';",
      "import PropTypes from 'prop-types'",
      "",
      "const componentName = (props) => {",
      "  return (<div></div>)",
      "}",
      "",
      "componentName.propTypes = {};",
      "",
      "componentName.defaultProps = {};",
      "",
      "export default componentName;"
    ],
    "description": "React Functional Component"
  }
```


#### Jest Snapshot Test Component

```javascript
import React from 'react';
import { shallow } from 'enzyme';

describe('Component Test', () => {
  it('renders without crashing', () => {
    shallow(<COMPONENT />);
  });
  it('renders with snapshot correctly', () => {
    const wrapper = shallow(<COMPONENT />);
    expect(wrapper).toMatchSnapshot();
  });
});
```

### Code Snippet - React Snapshot test component

```
"React Snapshot Test Component": {
    "prefix": "RSTC",
    "body": [
      "import React from 'react';",
      "import { shallow } from 'enzyme';",
      "",
      "describe('Component Test', () => {",
      "  it('renders without crashing', () => {",
      "    shallow(<COMPONENT />);",
      "  });",
      "  it('renders with snapshot correctly', () => {",
      "    const wrapper = shallow(<COMPONENT />);",
      "    expect(wrapper).toMatchSnapshot();",
      "  });",
      "});",
      ""
    ],
    "description": "React Snapshot test component"
  }
```
