<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="ux0iofbdv"/><path class="d-ykg1bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:sagittarius" {...props}></Icon>
<style>
:global(.d-ykg1bnb) {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--fff, #fff);
  stroke-miterlimit: 10;
  d: path("M48 17.4c-.1-.8-.6-1.4-1.4-1.4H32c-1.9 0-1.9 2.9 0 2.9h11L24.7 37.2L18.5 31c-1.3-1.3-3.4.7-2.1 2.1l6.2 6.2l-6.2 6.2c-.4.5-.5 1.1-.2 1.5q.3.75 1.2.9h.4c.1 0 .1 0 .2-.1c.1 0 .1-.1.2-.1c.1-.1.2-.1.2-.2l6.2-6.2l6.2 6.2c1.3 1.3 3.4-.7 2.1-2.1l-6.2-6.2c6.2-6 12.3-12.1 18.4-18.2v11c0 1.9 2.9 1.9 2.9 0z");
}

:global(.ux0iofbdv) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--428bc1, #428bc1);
}

</style>
