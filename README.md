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

The moment a commit is pushed to the repo, codeship starts the build process.



---- 

1. Amazon
    - set up a user
    - use user credentials in codeship
    - create an elastic beanstalk 
    - enter 
    - create an elastic beanstalk instance -- 
  
 Codeship 
      In the deplyment pipeline the S3 is a staging state where amazon uses to temporary store the data before putting into 
      
      
      
Elastic -> All apps -> myapp
      configuration 
              node command ---> npm start 
        
         
         
         
 User of Packer
      see github.com/adron/multi-cloud
      
      use connection.tf
      
