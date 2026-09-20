<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwh_96bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:takeout-dining" {...props}></Icon>
<style>
:global(.nwh_96bqo) {
  fill: currentColor;
  d: path("M4.625 10L2 7.45l1.4-1.4L5 7.65l-.05-.6L9 3h6l4.05 4.05l-.05.6l1.6-1.6l1.4 1.4L19.375 10zM5.95 20l-.65-8.45h13.4L18.05 20z");
}

</style>
