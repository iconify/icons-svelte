<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf3_r800o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-align-horizontal-left" {...props}></Icon>
<style>
:global(.yf3_r800o) {
  fill: currentColor;
  d: path("M4 22H2V2h2zM22 7H6v3h16zm-6 7H6v3h10z");
}

</style>
