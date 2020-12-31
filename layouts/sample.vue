<template>
  <div>
    <ex-header />
    <nuxt />
    <ex-footer />
  </div>
</template>

<script>
// ヘッダ＆フッタをインポート
import ExHeader from '~/components/header.vue'
import ExFooter from '~/components/footer.vue'

export default {
  name: 'sample',	// テンプレート名
  components: {
    ExHeader,		// <ex-header>に対応
    ExFooter		// <ex-footer>に対応
  }
}
</script>