<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf-8_76gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-new-label" {...props}></Icon>
<style>
:global(.bf-8_76gq) {
  fill: currentColor;
  d: path("m21 12l-4.97 7H12v-6H9v-3H3V5h13.03zm-11 3H7v-3H5v3H2v2h3v3h2v-3h3z");
}

</style>
