<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a93huobqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-align-horizontal-right" {...props}></Icon>
<style>
:global(.a93huobqi) {
  fill: currentColor;
  d: path("M20 2h2v20h-2zM2 10h16V7H2zm6 7h10v-3H8z");
}

</style>
