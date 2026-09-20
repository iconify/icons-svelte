<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbm2u_bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:split-scene-left-sharp" {...props}></Icon>
<style>
:global(.vbm2u_bkj) {
  fill: currentColor;
  d: path("M14.885 19V5H20v14zM11.5 21v-2H4V5h7.5V3h1v18z");
}

</style>
