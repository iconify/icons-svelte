<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyzj50unz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-burst-mode" {...props}></Icon>
<style>
:global(.dyzj50unz) {
  fill: currentColor;
  d: path("M1 5h2v14H1zm4 0h2v14H5zm18 0H9v14h14zM11 17l2.5-3.15L15.29 16l2.5-3.22L21 17z");
}

</style>
