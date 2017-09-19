## paymentspring checkout form

The checkout form is a simple way to seamlessly integrate the checkout button's ease of use natively into your site.

The form elements are placed along side your html making the form part of your user experience and ultimately gives you the control.

Each form is configurable with all the options found on our [button examples page](https://paymentspring.github.io/checkout-examples/).

### Example

{% include shared-copy/example-script-tag.html type="form" %}

In addition to the javascript above, you will need to paste a link to our stylesheet (css) in the head of your site. If you plan to style the form, see styling below, please place this link before other css links.

```markdown
<link rel="stylesheet" type="text/css" href="https://checkout.paymentspring.com/assets/application.css">
```

{% include inline-checkout/inline-script.html %}

### Styling

One of the cool things about using the inline checkout form is that it is completely customizable to fit your site. By including the link to our stylesheet before your own you can easily override css rules to add colors, change sizes, and make our form your own.

Here is an example that updates the inline checkout form to match the colors of the page.

{% include inline-checkout/inline-example-image.html %}

The sass (compiled to css) to accomplish the above looks like this.

```
$orange: #e95420;
$light-orange: #f3a386;

.paymentspring-form {
  .paymentspring-inline {
    // tab navigation for payment methods
    a {
      font-size: 14px;
      color: $orange;
      &:hover, &:active, &:focus {
        color: $orange;
      }
    }

    .container {
      .paymentspring-sub-container {
        .paymentspring-content {
          .form-group {
            // tooltip for fee explaination
            .paymentspring-forced-fee {
              .paymentspring-fee-item {
                .glyphicon {
                  color: $orange;
                }
              }
            }
          }

          // checkboxes
          .cbx-active {
            color: $orange;
          }

          // distribution amount prompts
          .paymentspring-distributions {
            .paymentspring-option-container {
              .paymentspring-option {
                .paymentspring-specify-amount-prompt {
                  color: $orange
                }
              }
            }
          }
        }
      }
    }
  }

  // submit button
  .btn {
    &.btn-primary {
      background-color: $orange;
      border-color: $orange;
      &:hover, &:active, &:focus {
        background-color: $light-orange !important;
        border-color: $light-orange !important;
      }
    }
  }

  // success display
  .paymentspring-svg-success {
    stroke: $orange;
  }
}
```

### Support or Contact

Just getting started with paymentspring, or having a problem? [Contact us](https://paymentspring.com/contact/) or checkout [our docs](https://paymentspring.com/developers/)!
