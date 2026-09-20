<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1v8azb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sd-card-alert-sharp" {...props}></Icon>
<style>
:global(.f1v8azb5r) {
  fill: currentColor;
  d: path("M11 17h2v-2h-2zm0-4h2V8h-2zm9 9H4V8l6-6h10z");
}

</style>
