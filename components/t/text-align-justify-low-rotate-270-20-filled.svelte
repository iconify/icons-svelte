<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a7v3nrbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-justify-low-rotate-270-20-filled" {...props}></Icon>
<style>
:global(.a7v3nrbeq) {
  fill: currentColor;
  d: path("M4.5 11a.75.75 0 0 1-.75-.75v-7.5a.75.75 0 0 1 1.5 0v7.5a.75.75 0 0 1-.75.75m5 0a.75.75 0 0 1-.75-.75v-7.5a.75.75 0 0 1 1.5 0v7.5a.75.75 0 0 1-.75.75m4.25 6.25a.75.75 0 0 0 1.5 0V2.75a.75.75 0 0 0-1.5 0z");
}

</style>
