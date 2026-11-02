<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eu--urbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:vector-square-fill-round" {...props}></Icon>
<style>
:global(.eu--urbsm) {
  fill: currentColor;
  d: path("M7.829 4h8.342A3 3 0 1 1 20 7.829v8.342A3 3 0 1 1 16.171 20H7.829A3 3 0 1 1 4 16.171V7.829A3 3 0 1 1 7.829 4M6 7.829v8.342A3.01 3.01 0 0 1 7.829 18h8.342A3.01 3.01 0 0 1 18 16.171V7.829A3 3 0 0 1 16.171 6H7.829A3 3 0 0 1 6 7.829");
}

</style>
