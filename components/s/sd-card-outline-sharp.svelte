<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpejrdbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sd-card-outline-sharp" {...props}></Icon>
<style>
:global(.cpejrdbip) {
  fill: currentColor;
  d: path("M9 11h2V7H9zm3 0h2V7h-2zm3 0h2V7h-2zM4 22V8l6-6h10v20zm2-2h12V4h-7.15L6 8.85zm0 0h12z");
}

</style>
