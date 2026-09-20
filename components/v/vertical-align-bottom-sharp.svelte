<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccm26ub5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:vertical-align-bottom-sharp" {...props}></Icon>
<style>
:global(.ccm26ub5x) {
  fill: currentColor;
  d: path("M4 21v-2h16v2zm8-4l-5-5l1.4-1.4l2.6 2.6V3h2v10.2l2.6-2.6L17 12z");
}

</style>
