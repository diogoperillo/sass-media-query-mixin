# sass-media-query-mixin
Sass Media Query Mixin

This is a simple mixin to help using sass on responsive layouts

``` sass
//Example of usage

.app-style {
  //Creating a Style for mobile only
  @include media(mobile) {
    max-width: 500px;
    //Creating a Style for mobile only and retina only
    @include media(retina) {
      border-top: 2px;
    }
  }
  
  //Creating a Style for desktop or tablet
  @include media(desktop, tablet) {
    min-width: 500px;
  }
}
```
