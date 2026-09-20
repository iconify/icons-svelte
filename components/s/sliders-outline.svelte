<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynvn33bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sliders-outline" {...props}></Icon>
<style>
:global(.ynvn33bgy) {
  fill: currentColor;
  d: path("M5 15q-1.25 0-2.125-.875T2 12t.875-2.125T5 9h14q1.25 0 2.125.875T22 12t-.875 2.125T19 15zm9-2h5q.425 0 .713-.288T20 12t-.288-.712T19 11h-5z");
}

</style>
