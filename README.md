JavaScript Resources
The React documentation assumes some familiarity with programming in the JavaScript language. You don’t have to be an expert, but it’s harder to learn both React and JavaScript at the same time.

We recommend going through this JavaScript overview to check your knowledge level. It will take you between 30 minutes and an hour but you will feel more confident learning React.


## Overview
React lets you define components as classes or functions. Components defined as classes currently provide more features which are described in detail on this page. To define a React component class, you need to extend React.Component:
class Welcome extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}</h1>;
  }
}

The only method you must define in a React.Component subclass is called render(). All the other methods described on this page are optional.
We strongly recommend against creating your own base component classes. In React components, code reuse is primarily achieved through composition rather than inheritance.


