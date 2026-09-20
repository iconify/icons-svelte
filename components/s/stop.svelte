<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocemagb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stop" {...props}></Icon>
<style>
:global(.ocemagb_f) {
  fill: currentColor;
  d: path("M6 18V6h12v12z");
}

</style>
