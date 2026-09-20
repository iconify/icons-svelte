<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ywmiohuuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:tbtc" {...props}></Icon>
<style>
:global(.ywmiohuuk) {
  fill: var(--svg-color--090502, #090502);
  fill-rule: evenodd;
  d: path("M21 12a9 9 0 1 1-18 0a9 9 0 0 1 18 0m-2.118 0a6.882 6.882 0 1 1-13.764 0a6.882 6.882 0 0 1 13.764 0M13.06 8.824a1.059 1.059 0 1 1-2.118 0a1.059 1.059 0 0 1 2.118 0m2.118 2.647H8.824v1.058h2.646v3.177h1.06v-3.177h2.647z");
}

</style>
