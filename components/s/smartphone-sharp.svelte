<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwizc5bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:smartphone-sharp" {...props}></Icon>
<style>
:global(.jwizc5bwk) {
  fill: currentColor;
  d: path("M6 22V2h12v20zm1-3.5h10v-13H7z");
}

</style>
