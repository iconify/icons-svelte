<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1f6mbbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:vertical-align-bottom" {...props}></Icon>
<style>
:global(.v1f6mbbnl) {
  fill: currentColor;
  d: path("M5 20v-1h14v1zm7-3.692L7.692 12l.708-.708l3.1 3.1V4h1v10.392l3.1-3.1l.708.708z");
}

</style>
