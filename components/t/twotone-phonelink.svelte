<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks6zp8urd"/><path class="lbw5-vblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-phonelink" {...props}></Icon>
<style>
:global(.ks6zp8urd) {
  fill: currentColor;
  d: path("M18 10h4v7h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.lbw5-vblf) {
  fill: currentColor;
  d: path("M4 6h18V4H4c-1.1 0-2 .9-2 2v11H0v3h14v-3H4zm19 2h-6c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h6c.55 0 1-.45 1-1V9c0-.55-.45-1-1-1m-1 9h-4v-7h4z");
}

</style>
