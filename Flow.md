Flow
===================

***React와 Flow***

* Props & State

```javascript
type Props = {
	foo: number,
	poo: Array<{a: number, b: string}>
};

type State = {
	bar: string
};

class MyComponent extends React.Component<Props, State> {}
```

* defaultProps

```javascript
// class component
static defaultProps = {
	foo: 'bar'
}

// functional component
MyComponent.defaultProps = {
	foo: 'bar'
}
```

* Array

```javascript
arr1: Array<{obj1: string, obj2: number}>
```
