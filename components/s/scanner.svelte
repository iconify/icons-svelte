<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bldpf2bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:scanner" {...props}></Icon>
<style>
:global(.bldpf2bqx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 18.7V9.5c0-2.2-1.8-4-4-4h-29c-2.2 0-4 1.8-4 4v9.2m0 10.6v9.2c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-9.2M5.5 24h37");
}

</style>
