<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul466sbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:screenshot-frame-outline-sharp" {...props}></Icon>
<style>
:global(.ul466sbtu) {
  fill: currentColor;
  d: path("M5 7V2h5v2H7v3zm0 15v-5h2v3h3v2zM17 7V4h-3V2h5v5zm-3 15v-2h3v-3h2v5z");
}

</style>
