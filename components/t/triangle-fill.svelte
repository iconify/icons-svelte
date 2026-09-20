<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="o2ujj_2pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:triangle-fill" {...props}></Icon>
<style>
:global(.o2ujj_2pq) {
  fill: currentColor;
  d: path("M236.78 211.81A24.34 24.34 0 0 1 215.45 224H40.55a24.34 24.34 0 0 1-21.33-12.19a23.51 23.51 0 0 1 0-23.72l87.43-151.87a24.76 24.76 0 0 1 42.7 0l87.45 151.87a23.51 23.51 0 0 1-.02 23.72");
}

</style>
