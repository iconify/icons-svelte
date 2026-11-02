<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p12fh_5_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skip-back-fill-sharp" {...props}></Icon>
<style>
:global(.p12fh_5_o) {
  fill: currentColor;
  d: path("M5 19a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0ZM19.496 4.136A1.002 1.002 0 0 1 21 5v14a.998.998 0 0 1-1.504.864l-12-7a1 1 0 0 1 0-1.728Z");
}

</style>
