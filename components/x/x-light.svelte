<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ie2aq5xjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:x-light" {...props}></Icon>
<style>
:global(.ie2aq5xjr) {
  fill: currentColor;
  d: path("M204.24 195.76a6 6 0 1 1-8.48 8.48L128 136.49l-67.76 67.75a6 6 0 0 1-8.48-8.48L119.51 128L51.76 60.24a6 6 0 0 1 8.48-8.48L128 119.51l67.76-67.75a6 6 0 0 1 8.48 8.48L136.49 128Z");
}

</style>
