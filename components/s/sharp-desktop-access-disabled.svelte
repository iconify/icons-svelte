<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsk1v0bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-desktop-access-disabled" {...props}></Icon>
<style>
:global(.nsk1v0bil) {
  fill: currentColor;
  d: path("M1.41 1.69L0 3.1l1 .99V18h9v2H8v2h8v-2h-2v-2h.9l6 6l1.41-1.41zM2.99 16V6.09L12.9 16zM4.55 2l2 2H21v12h-2.45l2 2h2.44V2z");
}

</style>
