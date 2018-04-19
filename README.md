**Maintainer:** Michael Heigl <br />
**Plugin Website:** https://github.com/mheigl/bootstrap4-input-clearer <br />

<br />

## About
This jQuery plugin adds a clear icon to input fields for your Bootstrap 4 enabled website.

## Getting Started

#### Direct Download
 * [zip](https://github.com/mheigl/bootstrap4-input-clearer/archive/master.zip)
 * [tarbell](https://github.com/mheigl/bootstrap4-input-clearer/archive/master.tar.gz)
 * Individual Files
    * [bootstrap4-input-clearer.js](https://raw.githubusercontent.com/mheigl/bootstrap4-input-clearer/master/bootstrap4-input-clearer.js)
    * [bootstrap4-input-clearer.min.js](https://raw.githubusercontent.com/mheigl/bootstrap4-input-clearer/master/bootstrap4-input-clearer.min.js)

**Note**: bootstrap4-input-clearer has a dependency on jquery 3.1+ and Bootstrap 4

#### NPM
Install with [NPM](http://npmjs.org):
```bash
npm install bootstrap4-input-clearer
```

#### Github
Clone the [boostrap4-input-clearer](https://github.com/mheigl/bootstrap4-input-clearer/):
```bash
git clone git@github.com:mheigl/bootstrap4-input-clearer.git
```

### Available Options

<table>
  <tr>
    <th>Option</th>
    <th>Type</th>
    <th>Default</th>
  </tr>
  <tr>
    <td>clearHtml</td>
    <td>string</td>
    <td>&times;</td>
  </tr>
  <tr>
    <td>cssClass</td>
    <td>string</td>
    <td>input-clearer</td>
  </tr>
</table>

#### Using Options
```javascript
$("input").clearer();

// Example option usage
$("input").clearer({
  clearHtml: "click me"
});

```
