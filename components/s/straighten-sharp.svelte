<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykk9pcb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:straighten-sharp" {...props}></Icon>
<style>
:global(.ykk9pcb4h) {
  fill: currentColor;
  d: path("M3 17V7h4.5v4.23h1V7h3v4.23h1V7h3v4.23h1V7H21v10z");
}

</style>
