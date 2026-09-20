<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8sjy7wwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:vertical-align-top-outline" {...props}></Icon>
<style>
:global(.a8sjy7wwc) {
  fill: currentColor;
  d: path("M4 5V3h16v2zm7 16V10.8l-2.6 2.6L7 12l5-5l5 5l-1.4 1.4l-2.6-2.6V21z");
}

</style>
