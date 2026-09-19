<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gsno7hb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sai-alt" {...props}></Icon>
<style>
:global(.gsno7hb6c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.914 43.5l6.957-7.64H16.956zm0-7.64V17.929L37.343 4.5m-17.098 9.761l-9.588-9.588");
}

</style>
