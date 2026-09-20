<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="wdir-mb6a"/><path class="vzqbozhzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:user-square-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.vzqbozhzd) {
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16M96 120a32 32 0 1 1 32 32a32 32 0 0 1-32-32m-27.33 88a64.45 64.45 0 0 1 19.13-25.8a64 64 0 0 1 80.4 0a64.45 64.45 0 0 1 19.13 25.8ZM208 208h-3.67a79.87 79.87 0 0 0-46.69-50.29a48 48 0 1 0-59.28 0A79.87 79.87 0 0 0 51.67 208H48V48h160z");
}

:global(.wdir-mb6a) {
  d: path("M208 40H48a8 8 0 0 0-8 8v160a8 8 0 0 0 8 8h160a8 8 0 0 0 8-8V48a8 8 0 0 0-8-8M57.78 216A72 72 0 0 1 128 160a40 40 0 1 1 40-40a40 40 0 0 1-40 40a72 72 0 0 1 70.22 56Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
