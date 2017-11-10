1. What is the difference between server side routing and client side routing?
    Server side routing will only request data that is needed. It refreshes a whole page to be rendered/refreshed.
    Client side routing is handled internally by js. It only loads the portion where it needs to be changed.

2. Mention some advantages of using client side routing.
    Some advantages to using client side routing is that it is generally more efficient. Since there is less data to be processed, it is able to load faster.
    
3. Which component is used to define a route and what props are commonly added to it?
    <Route path = '' components={} />
    Common props include mapStateToProps
    
4. How can I make sure that the component associated with the "/" is not displayed for every other route?
    You can the a strict equal by inserting 'exact' to the path.
