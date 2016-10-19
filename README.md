# course

A simple node application to show how continous deployment using codeship workrs.

# steps followed

## initialise an express application

``` express . ```

## add a moch test

``` mkdir test ```

``` touch fancyTest.js ```

```
var assert = require('assert');
describe('Array', function() {
  describe('#indexOf()', function() {
    it('should return -1 when the value is not present', function() {
      assert.equal(-1, [1,2,3].indexOf(4));
    });
  });
});
```
