<template>
<div class="card-right">
  <card-right-top/>
  <card-right-bottom/>
</div>
</template>

<script>
import CardRightTop from "@/components/card/card-right/item/card-right-top";
import CardRightBottom from "@/components/card/card-right/item/card-right-bottom";
export default {
  name: "CardRight",
  components: {CardRightTop, CardRightBottom}
}
</script>

<style scoped>

</style>