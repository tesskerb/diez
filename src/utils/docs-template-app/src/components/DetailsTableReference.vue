<template>
  <router-link v-if="reference" :to="reference.link"><pill>{{reference.idPath.join('.')}}</pill></router-link>
</template>

<script lang="ts">
import Pill from '@/components/Pill.vue';
import {Component, Prop, Vue} from 'vue-property-decorator';
import {DocsReference} from '../api';

/**
 * Shows inline references for components.
 */
@Component({
  components: {
    Pill,
  },
})
export default class DetailsTableReference extends Vue {
  @Prop() protected reference!: DocsReference;
}
</script>
