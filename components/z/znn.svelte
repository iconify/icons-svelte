<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c-mxhbbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:znn" {...props}></Icon>
<style>
:global(.c-mxhbbkg) {
  fill: var(--svg-color--00ff65, #00ff65);
  fill-rule: evenodd;
  d: path("M6.375 3h11.25v2.16l-6.868 4.59h6.868V21h-2.036l-6.964-5.962V21h-2.25V9.682l7.037-4.432H6.375zm2.25 9h6.75v5.625z");
}

</style>
