## paymentspring checkout button

The checkout button is the easiest way to start accepting payments on your
website with paymentspring.

Checkout buttons are configurable (see options below), and multiple checkout
buttons can be included on a single web page.

### Example

{% include shared-copy/example-script-tag.html type="button" %}

### Options

static amount:
{% include checkout-buttons/static-amount.html %}

dynamic amount:
{% include checkout-buttons/dynamic-amount.html %}

recurring checkbox:
{% include checkout-buttons/checkbox.html %}

optional additional donation:
(only available to charitable, social service, and religious organizations)
{% include checkout-buttons/transaction_fee_optional.html %}

static distribution:
{% include checkout-buttons/static-distribution.html %}

dynamic distribution:
{% include checkout-buttons/dynamic-distribution.html %}

### Javascript callback

{% include shared-copy/example-js-callback.html type="button" %}

### Support or Contact

Just getting started with paymentspring, or having a problem? [Contact
us](https://paymentspring.com/contact/) or checkout [our
docs](https://paymentspring.com/developers/)!
