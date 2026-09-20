<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6r152bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:security-update-good-sharp" {...props}></Icon>
<style>
:global(.k6r152bnl) {
  fill: currentColor;
  d: path("M11.05 14.308L8.942 12.2l.708-.708l1.4 1.4l3.55-3.55l.708.708zM6 22V2h12v20zm1-3.5h10v-13H7z");
}

</style>
