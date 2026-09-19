<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c50kwtbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-security-update" {...props}></Icon>
<style>
:global(.c50kwtbiw) {
  fill: currentColor;
  d: path("M5 1v22h14V1zm12 17H7V6h10zm-1-6h-3V8h-2v4H8l4 4z");
}

</style>
