# ShoppingGives Tag manager

An easy way to track clicks on the ShoppingGives Widget.

This custom tag allows you to track all the ShoppingGives Widget interactions, without the hassle of configuring each tag.

The tag needs your GA Tracking ID to collect the data correctly. 

The tag also requires two triggers to function propperly:

  - An Element Visibility trigger with the following configuration:
    - Selection method: CSS Selector
    - Element selector: .sg-widget
    - When to fire this trigger: Once per page

  - A Click trigger that fires on all clicks
