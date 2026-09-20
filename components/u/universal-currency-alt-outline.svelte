<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2cwmvjhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:universal-currency-alt-outline" {...props}></Icon>
<style>
:global(.c2cwmvjhp) {
  fill: currentColor;
  d: path("M15 16h4v-4h-1.5v2.5H15zm-3-1q1.25 0 2.125-.875T15 12t-.875-2.125T12 9t-2.125.875T9 12t.875 2.125T12 15m-7-3h1.5V9.5H9V8H5zm-3 7V5h20v14zm2-2h16V7H4zm0 0V7z");
}

</style>
