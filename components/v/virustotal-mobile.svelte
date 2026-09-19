<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vkfli2bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:virustotal-mobile" {...props}></Icon>
<style>
:global(.vkfli2bgh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.232 11.573l-3.5-6.073l-28.51 8.093l21.41 9.413L15.14 42.5l26.638-7.162v-1.982");
}

</style>
