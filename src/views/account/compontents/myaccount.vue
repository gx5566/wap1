<template>
  <div>
    <div class="wishlist">
        <flexbox>
        <flexbox-item class="t_size">
              <div class="flex-demo">1</div>
              <div class="flex-demo" v-text="$t('我的关注')"></div>
          </flexbox-item>
          <flexbox-item class="t_size">
              <div class="flex-demo">2</div>
              <div class="flex-demo" v-text="$t('消息中心')"></div>
          </flexbox-item>
          <flexbox-item class="t_size">
              <div class="flex-demo">3</div>
              <div class="flex-demo" v-text="$t('浏览历史')"></div>
          </flexbox-item>
        </flexbox>
      </div> 
  </div>
</template>
<i18n>
我的关注:
 en: My wishlist
消息中心:
 en: My message
浏览历史:
  en: Browsing history
</i18n>

<script>
import { Flexbox, FlexboxItem, Divider } from 'vux'

export default {
  components: {
    Flexbox,
    FlexboxItem,
    Divider
  }
}
</script>
<style>

</style>
