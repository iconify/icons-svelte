<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmtsv_v6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:straighten-outline-sharp" {...props}></Icon>
<style>
:global(.mmtsv_v6a) {
  fill: currentColor;
  d: path("M3 17V7h18v10zm1-1h16V8h-3.5v3.23h-1V8h-3v3.23h-1V8h-3v3.23h-1V8H4zm3.5-4.77h1zm4 0h1zm4 0h1zM12 12");
}

</style>
