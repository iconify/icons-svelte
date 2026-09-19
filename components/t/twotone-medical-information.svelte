<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4uum8b5l"/><path class="am6vf1bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-medical-information" {...props}></Icon>
<style>
:global(.am6vf1bhc) {
  fill: currentColor;
  d: path("M20 7h-5V4c0-1.1-.9-2-2-2h-2c-1.1 0-2 .9-2 2v3H4c-1.1 0-2 .9-2 2v11c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V9c0-1.1-.9-2-2-2m-9-3h2v5h-2zm9 16H4V9h5c0 1.1.9 2 2 2h2c1.1 0 2-.9 2-2h5zm-9-4H9v2H7v-2H5v-2h2v-2h2v2h2zm2-1.5V13h6v1.5zm0 3V16h4v1.5z");
}

:global(.d4uum8b5l) {
  fill: currentColor;
  d: path("M15 9c0 1.1-.9 2-2 2h-2c-1.1 0-2-.9-2-2H4v11h16V9zm-4 7H9v2H7v-2H5v-2h2v-2h2v2h2zm6 1.5h-4V16h4zm2-3h-6V13h6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
