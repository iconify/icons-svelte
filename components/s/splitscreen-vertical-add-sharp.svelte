<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sml-xjopw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:splitscreen-vertical-add-sharp" {...props}></Icon>
<style>
:global(.sml-xjopw) {
  fill: currentColor;
  d: path("M3 21V3h8v18zm10 0V3h8v12.1q-.25-.05-.5-.075T20 15q-2.075 0-3.537 1.45T15 19.975q0 .275.025.525t.075.5zm6 2v-2h-2v-2h2v-2h2v2h2v2h-2v2z");
}

</style>
