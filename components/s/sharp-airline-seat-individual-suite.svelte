<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6kf2yryt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-airline-seat-individual-suite" {...props}></Icon>
<style>
:global(.z6kf2yryt) {
  fill: currentColor;
  d: path("M7 13c1.65 0 3-1.35 3-3S8.65 7 7 7s-3 1.35-3 3s1.35 3 3 3m16-6H11v7H3V7H1v10h22z");
}

</style>
