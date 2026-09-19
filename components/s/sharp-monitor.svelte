<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdzxtab2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-monitor" {...props}></Icon>
<style>
:global(.zdzxtab2f) {
  fill: currentColor;
  d: path("M22 3H2v15h5l-1 1v2h12v-2l-1-1h5zm-2 13H4V5h16z");
}

</style>
