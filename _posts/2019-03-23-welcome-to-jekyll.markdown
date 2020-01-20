---
layout: post
title:  "Integrating razorpay into your webapp"
categories: Javascript NodeJS
---
introduce

```javascript
const Razorpay = require('razorpay');

let rzp = Razorpay({
	key_id: 'KEY_ID',
	secret: 'name'
});

// capture request
rzp.capture(payment_id, cost)
	.then(function (data) {
		return 2;
	})
```

Check out the [bkf]

[bkf]: https://github.com/Roshanson/TextInfoExp

