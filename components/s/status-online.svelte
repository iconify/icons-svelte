<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pha4gg2xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:status-online" {...props}></Icon>
<style>
:global(.pha4gg2xa) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 12q0 3.21 2.27 5.48T12 19.75t5.48-2.27T19.75 12t-2.27-5.48T12 4.25T6.52 6.52T4.25 12");
}

</style>
