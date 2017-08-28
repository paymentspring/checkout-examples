## paymentspring checkout

The checkout button is the easiest way to start accepting payments on your website with paymentspring.

Checkout buttons are configurable (see options below), and multiple checkout buttons can be included on a single web page.

### Example

To include a checkout button on a page, you will need a checkout form-id. Once you have a form-id, paste this javascript into your site where you would like the form to appear:

```markdown
<script src="https://checkout.paymentspring.com/js/paymentspring.js" formid="cb7eae32763131ade35f"></script>
```
Where `cb7eae32763131ade35f` is your form-id.

### Options

static amount (with ach):
{% include checkout-buttons/static-amount.html %}

dynamic amount:
{% include checkout-buttons/dynamic-amount.html %}

recurring checkbox:
{% include checkout-buttons/checkbox.html %}

static distribution (with ach):
{% include checkout-buttons/static-distribution.html %}

dynamic distribution:
{% include checkout-buttons/dynamic-distribution.html %}


### Support or Contact

Just getting started with paymentspring, or having a problem? [Contact us](https://paymentspring.com/contact/) or checkout [our docs](https://paymentspring.com/developers/)!
