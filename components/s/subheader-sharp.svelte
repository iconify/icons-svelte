<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bopwhvbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:subheader-sharp" {...props}></Icon>
<style>
:global(.bopwhvbfp) {
  fill: currentColor;
  d: path("M6 10h9V7H6zM3 21V3h18v18z");
}

</style>
