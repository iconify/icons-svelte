<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m07boihme"/><path class="de6ql-bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-topic" {...props}></Icon>
<style>
:global(.de6ql-bfl) {
  fill: currentColor;
  d: path("M20 6h-8l-2-2H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16.77c.68 0 1.23-.56 1.23-1.23V8c0-1.1-.9-2-2-2m0 12H4V6h5.17l2 2H20zm-2-6H6v-2h12zm-4 4H6v-2h8z");
}

:global(.m07boihme) {
  fill: currentColor;
  d: path("M20 18H4V6h5.17l2 2H20zm-2-6H6v-2h12zm-4 4H6v-2h8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
