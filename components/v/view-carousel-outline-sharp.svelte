<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6twkgk3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-carousel-outline-sharp" {...props}></Icon>
<style>
:global(.v6twkgk3g) {
  fill: currentColor;
  d: path("M2 17V7h4v10zm5 2V5h10v14zm11-2V7h4v10zm-9 0h6V7H9zm3-5");
}

</style>
