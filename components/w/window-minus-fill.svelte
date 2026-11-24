<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnyzeqghk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-minus-fill" {...props}></Icon>
<style>
:global(.gnyzeqghk) {
  fill: currentColor;
  d: path("M19 21H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3M4 9v9a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1V9Zm5 4h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
