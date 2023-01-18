<template>
  <div class="card">
  <card-right/>
  <card-left/>
  </div>
</template>

<script>
import CardRight from "@/components/card/card-right";
import CardLeft from "@/components/card/card-left";
export default {
  name: "Card",
  components: {CardLeft, CardRight}

}
</script>

<style lang="scss" scoped>
.card{
  display: flex;
  align-items: center;
  width: 100%;
  max-width: 880px;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.15);
  border-radius: 4px;
  justify-content: space-between;
}
</style>