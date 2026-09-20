<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8be6abhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:video-label-sharp" {...props}></Icon>
<style>
:global(.k8be6abhw) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-5h16V6H4z");
}

</style>
