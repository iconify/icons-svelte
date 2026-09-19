<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g-s-0hbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:yrc-setting" {...props}></Icon>
<style>
:global(.g-s-0hbjt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.053 11.269H43.5M15.053 36.731H43.5M15.053 14.452H43.5m-28.447 3.182H43.5m-28.447 3.183H43.5M15.053 24H43.5m-28.447 3.183H43.5m-28.447 3.183H43.5m-28.447 3.182H43.5M13.919 17.634L4.5 23.072V12.197z");
}

</style>
