<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znnsddche"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:toast-sharp" {...props}></Icon>
<style>
:global(.znnsddche) {
  fill: currentColor;
  d: path("M6 18h12v-2H6zm-3 3V3h18v18z");
}

</style>
