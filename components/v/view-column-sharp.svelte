<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da219mu4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-column-sharp" {...props}></Icon>
<style>
:global(.da219mu4s) {
  fill: currentColor;
  d: path("M3 19V5h5.325v14zm6.325 0V5h5.325v14zm6.325 0V5h5.325v14z");
}

</style>
