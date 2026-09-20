<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cbl3o-b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:square-32-filled" {...props}></Icon>
<style>
:global(.cbl3o-b9h) {
  fill: currentColor;
  d: path("M7.5 3A4.5 4.5 0 0 0 3 7.5v17A4.5 4.5 0 0 0 7.5 29h17a4.5 4.5 0 0 0 4.5-4.5v-17A4.5 4.5 0 0 0 24.5 3z");
}

</style>
