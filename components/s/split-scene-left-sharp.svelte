<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-q_-0bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:split-scene-left-sharp" {...props}></Icon>
<style>
:global(.d-q_-0bar) {
  fill: currentColor;
  d: path("M15 20V4h6v16zm-4 2v-2H3V4h8V2h2v20z");
}

</style>
