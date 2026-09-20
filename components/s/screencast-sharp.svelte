<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx_mvdvmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:screencast-sharp" {...props}></Icon>
<style>
:global(.fx_mvdvmo) {
  fill: currentColor;
  d: path("M2 20V4h20v16Zm12-4v-2h4v2Zm0-3v-2h4v2ZM4 11v7h16v-8h-6V8h6V6h-8v5Z");
}

</style>
