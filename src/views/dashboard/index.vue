<template>
  <div class="dashboard-container">
    <!-- <component :is="currentRole"/> -->
  </div>
</template>

<script>
// import { mapGetters } from 'vuex'
// import adminDashboard from './admin'
// import editorDashboard from './editor'
import HelloWorld from '@/components/HelloWorld'

export default {
  name: 'HelloWorld',
  components: {HelloWorld},
  data () {
    return {
      currentRole: 'HelloWorld'
    }
  }
}
</script>
