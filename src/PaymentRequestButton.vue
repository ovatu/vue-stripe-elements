<template>
  <stripe-element
    ref="element"
    type="paymentRequestButton"
    :stripe="stripe"
    :options="options"
  />
</template>

<script>
import props from './props'
import StripeElement from './StripeElement'
export default {
  components: { StripeElement },
  props
}
</script>
