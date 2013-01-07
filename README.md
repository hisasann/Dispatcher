Sample
---
    Dispatcher
      .next("^/foo$", function() {
        console.log("foo");
      })
      .next("^/hoge$", function() {
        console.log("hoge");
      })
      .dispatch(location.pathname + location.search);


