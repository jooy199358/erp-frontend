<template>
    <div>
      <search-pager :option="option" :tools="tools"></search-pager>
    </div>
</template>

<script>
import searchPager from '../../components/query-table/search-pager';

export default {
  components: {
    searchPager,
  },
  data() {
    return {
      option: {
        back: '123',
      },
      tools: [
        {
          label: '刷新',
          icon: 'iconfont icon-refresh',
          show: true,
        },
        {
          label: '新增',
          icon: 'iconfont icon-plus',
          show: true,
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
</style>
