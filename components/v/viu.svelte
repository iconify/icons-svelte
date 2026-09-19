<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="efio_8bsc"/><path class="km5tg7bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:viu" {...props}></Icon>
<style>
:global(.efio_8bsc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.139 21.968v10.161m-4.804-16.258v16.258L4.5 15.871m24.165 0v10.873a5.385 5.385 0 0 0 5.385 5.385h4.065a5.385 5.385 0 0 0 5.385-5.385V15.87m-19.361 2.033v-2.032");
}

:global(.km5tg7bkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.971 21.968l-6.687-3.861v7.722z");
}

</style>
