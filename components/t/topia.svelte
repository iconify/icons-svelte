<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGM6grvbKY)" class="db4brot9t"/><defs><linearGradient id="SVGM6grvbKY" x1="6.072" x2="18.021" y1="4.906" y2="18.289" gradientUnits="userSpaceOnUse"><stop class="f1fzxhz7x"/><stop offset=".25" class="cskv3jb6d"/><stop offset=".51" class="v62blwbvo"/><stop offset=".73" class="fv6p7cbxf"/><stop offset="1" class="ixan_qb9t"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:topia" {...props}></Icon>
<style>
:global(.cskv3jb6d) {
  stop-color: var(--svg-color--d9fe35, #d9fe35);
}

:global(.db4brot9t) {
  d: path("M3.6 3h6.6v6h3.6V3h6.6v18h-6.6v-6h-3.6v6H3.6z");
}

:global(.f1fzxhz7x) {
  stop-color: var(--svg-color--ffa708, #ffa708);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.fv6p7cbxf) {
  stop-color: var(--svg-color--e4b685, #e4b685);
}

:global(.ixan_qb9t) {
  stop-color: var(--svg-color--f66aff, #f66aff);
}

:global(.v62blwbvo) {
  stop-color: var(--svg-color--9cfdde, #9cfdde);
}

</style>
