<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="faukaobnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-description-rtl-20-filled" {...props}></Icon>
<style>
:global(.faukaobnt) {
  fill: currentColor;
  d: path("M17.25 4.5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1 0-1.5zm0 3a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1 0-1.5zm.75 3.75a.75.75 0 0 0-.75-.75H2.75a.75.75 0 0 0 0 1.5h14.5a.75.75 0 0 0 .75-.75m-.75 2.25a.75.75 0 0 1 0 1.5h-9.5a.75.75 0 0 1 0-1.5z");
}

</style>
