<template>
  <div>
    <div class="bg-blue-50">hi 3</div>
    <ComponentWithApply/>
    <ComponentWithApply2/>
    <ComponentNoApply/>
  </div>
</template>

<script>
import ComponentWithApply from '../components/ComponentWithApply.vue';
import ComponentWithApply2 from '../components/ComponentWithApply2.vue';
import ComponentNoApply from '../components/ComponentNoApply.vue';

export default {
  name: 'IndexPage',
  components: {
    ComponentWithApply,
    ComponentWithApply2,
    ComponentNoApply
  }
}
</script>
