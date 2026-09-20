<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my3fcvb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tab-duplicate-outline-sharp" {...props}></Icon>
<style>
:global(.my3fcvb0z) {
  fill: currentColor;
  d: path("M6 18V2h16v16zm2-2h12V8h-7V4H8zM8 4v12zM6 22v-2h2v2zM4 6H2V4h2zm6 16v-2h2v2zm4 0v-2h2v2zM2 22v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V8h2v2zm16 10h2v2h-2z");
}

</style>
