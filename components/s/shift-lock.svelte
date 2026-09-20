<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bysp5t_fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:shift-lock" {...props}></Icon>
<style>
:global(.bysp5t_fv) {
  fill: currentColor;
  d: path("M9 16.616v-3.847H5.115L12 3.577l6.885 9.192H15v3.846zM5 20v-1h14v1z");
}

</style>
