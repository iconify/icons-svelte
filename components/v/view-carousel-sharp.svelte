<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8t8eji2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-carousel-sharp" {...props}></Icon>
<style>
:global(.n8t8eji2c) {
  fill: currentColor;
  d: path("M2 17V7h4v10zm5 2V5h10v14zm11-2V7h4v10z");
}

</style>
