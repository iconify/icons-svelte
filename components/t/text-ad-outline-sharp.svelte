<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r16isr4rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:text-ad-outline-sharp" {...props}></Icon>
<style>
:global(.r16isr4rh) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h16V6H4zm0 0V6zm1.73-2.116h12.54v-1H5.73zm0-3.384h12.54v-1H5.73zm0-3.384h8.77v-1H5.73z");
}

</style>
