<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc-n39buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:splitscreen-right-sharp" {...props}></Icon>
<style>
:global(.fc-n39buv) {
  fill: currentColor;
  d: path("M13.385 20V4h6v16zm-8.77 0V4h6v16zm1-15v14h4V5z");
}

</style>
