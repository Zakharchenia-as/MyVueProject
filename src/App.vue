<template>
  <div>
  <MenuTop/>
  <router-view/>
  <BotFooter/>
  </div>
</template>

<script>
import MenuTop from "@/components/templates/MenuTop"
import BotFooter from "@/components/templates/BotFooter"

export default{
  components:{
    MenuTop,
    BotFooter
  }
}
</script>