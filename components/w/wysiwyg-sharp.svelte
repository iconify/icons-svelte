<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o743r2b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:wysiwyg-sharp" {...props}></Icon>
<style>
:global(.o743r2b5i) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V7H5zm2-7.5v-1h10v1zm0 4v-1h6v1z");
}

</style>
