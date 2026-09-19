<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bhzwa_f4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sonolus" {...props}></Icon>
<style>
:global(.bhzwa_f4k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 9.5v4h37v-8h-33a4 4 0 0 0-4 4m0 4v11a4 4 0 0 0 4 4h33v-4a4 4 0 0 0-4-4h-25v-7zm29 15v6h-29v8h33a4 4 0 0 0 4-4v-10z");
}

</style>
