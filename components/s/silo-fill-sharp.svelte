<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2bpxpm-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:silo-fill-sharp" {...props}></Icon>
<style>
:global(.j2bpxpm-h) {
  fill: currentColor;
  d: path("M13 9.618V12H3V8a5 5 0 0 1 9.96-.638l7.487 3.744A1 1 0 0 1 21 12v8a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2v-2h10v2h6v-7.382ZM13 14v2H3v-2Z");
}

</style>
