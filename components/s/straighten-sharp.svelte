<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yysb2trkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:straighten-sharp" {...props}></Icon>
<style>
:global(.yysb2trkq) {
  fill: currentColor;
  d: path("M2 18V6h5v6h2V6h2v6h2V6h2v6h2V6h5v12z");
}

</style>
