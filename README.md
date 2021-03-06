# css-block-loader

[![npm version](https://badge.fury.io/js/css-block-loader.svg)](https://badge.fury.io/js/css-block-loader)

A stylish [css module](https://github.com/css-modules/css-modules) compatible block loader...

![](https://raw.githubusercontent.com/StevenIseki/css-block-loader/master/screenshot.png)

## Compatible

- [css modules](https://github.com/css-modules/css-modules)
- [react-css-modules](https://github.com/gajus/react-css-modules)

## Install

`npm install css-block-loader --save-dev`

## Usage

Simply import the block loader css module and use it as your loader, assign to your components' styles object:

```jsx
import loader from 'css-block-loader'
Object.assign(styles, loader)
```

Then use it for styling your elements.

```jsx
	return (
        <div className={styles.loader}>
            <span className={styles.block}></span>
            <span className={styles.block}></span>
            <span className={styles.block}></span>
            <span className={styles.block}></span>
            <span className={styles.block}></span>
            <span className={styles.block}></span>
            <span className={styles.block}></span>
            <span className={styles.block}></span>
            <span className={styles.block}></span>
        </div>
    );
```

## Example

Check out the full working example [here](https://github.com/StevenIseki/css-block-loader/tree/master/example)

**Run it**

`cd example; npm install; npm start`

## License

[MIT](http://isekivacenz.mit-license.org/)
