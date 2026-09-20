<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsb0_pb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:video-stable-sharp" {...props}></Icon>
<style>
:global(.nsb0_pb_t) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm14.975-2l2.3-8.65L7.075 6l-2.3 8.65z");
}

</style>
