<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcty2gb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tools-flat-head-outline-sharp" {...props}></Icon>
<style>
:global(.fcty2gb0e) {
  fill: currentColor;
  d: path("M8 21v-2h8v2zm0-3l-1-7l2-8h6l2 8l-1 7zm1.725-2h4.55l.55-4H9.15zM9.3 10h5.4l-1.25-5h-2.9zm4.975 6h-4.55z");
}

</style>
