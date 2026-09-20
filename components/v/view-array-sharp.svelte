<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5g5c4b9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-array-sharp" {...props}></Icon>
<style>
:global(.t5g5c4b9b) {
  fill: currentColor;
  d: path("M4 18V6h2.346v12zm3.73 0V6h8.54v12zm9.924 0V6H20v12z");
}

</style>
