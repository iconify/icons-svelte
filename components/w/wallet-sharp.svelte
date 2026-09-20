<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccuj2ebdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:wallet-sharp" {...props}></Icon>
<style>
:global(.ccuj2ebdj) {
  fill: currentColor;
  d: path("M2 20V4h20v16zM4 8h16V6H4zm11.775 6.075L20 10.525V10H4v1.225z");
}

</style>
