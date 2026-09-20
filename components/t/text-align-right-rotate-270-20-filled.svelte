<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oqqj0_blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-right-rotate-270-20-filled" {...props}></Icon>
<style>
:global(.oqqj0_blv) {
  fill: currentColor;
  d: path("M4.25 14a.75.75 0 0 1-.75-.75V2.75a.75.75 0 0 1 1.5 0v10.5a.75.75 0 0 1-.75.75m5 4a.75.75 0 0 1-.75-.75V2.75a.75.75 0 0 1 1.5 0v14.5a.75.75 0 0 1-.75.75m4.25-7.75a.75.75 0 0 0 1.5 0v-7.5a.75.75 0 0 0-1.5 0z");
}

</style>
