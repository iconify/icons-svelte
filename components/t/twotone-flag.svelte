<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fahtusbff"/><path class="isrkkfbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-flag" {...props}></Icon>
<style>
:global(.fahtusbff) {
  fill: currentColor;
  d: path("M12.36 6H7v6h7.24l.4 2H18V8h-5.24z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.isrkkfbce) {
  fill: currentColor;
  d: path("M14.4 6L14 4H5v17h2v-7h5.6l.4 2h7V6zm3.6 8h-3.36l-.4-2H7V6h5.36l.4 2H18z");
}

</style>
