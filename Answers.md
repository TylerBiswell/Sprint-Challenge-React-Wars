# Answers

1. What is React JS and what problems does it try and solve? Support your answer with concepts introduced in class and from your personal research on the web.

-- React JS is a library that builds upon vanilla JavaScript, utilizing the concept of components. It was built to allow developers to easily manipulate the DOM as well as *react* when certain data has changed, or functions have been fired.

1. What does it mean to think in react?

-- React is all about creating components that come together in the end. To think in React means to break apart a design into smaller components so that each module does its own things and rarely oversteps what another component may do.

1. Describe state.

-- State refers to the data of an application. Whenever something changes the data, the state of the application has changed.

1. Describe props.

-- Props is the concept of passing data from one component to the next.

1. What are side effects, and how do you sync effects in a React component to state or prop changes?

-- Side effects are anything that is out-of-scope for the component to handle. We utilize something called useEffect to monitor the state/prop changes so that it always executes a piece of code whenever the change occurs.