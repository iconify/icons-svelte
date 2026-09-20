<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="p84t_su2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:rows-bold" {...props}></Icon>
<style>
:global(.p84t_su2z) {
  fill: currentColor;
  d: path("M208 136H48a20 20 0 0 0-20 20v36a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20v-36a20 20 0 0 0-20-20m-4 52H52v-28h152Zm4-144H48a20 20 0 0 0-20 20v36a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V64a20 20 0 0 0-20-20m-4 52H52V68h152Z");
}

</style>
