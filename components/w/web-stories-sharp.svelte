<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5wwkguwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:web-stories-sharp" {...props}></Icon>
<style>
:global(.k5wwkguwp) {
  fill: currentColor;
  d: path("M17.116 19.596V4.385H18.5v15.211zm-13 1.635V2.769h12v18.462zM19.5 17.98V6h.885v11.98z");
}

</style>
