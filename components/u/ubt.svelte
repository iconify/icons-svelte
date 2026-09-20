<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGDpphpdxb)" class="iop1w-k-p"/><defs><linearGradient id="SVGDpphpdxb" x1="18.489" x2="5.771" y1="5.536" y2="18.335" gradientUnits="userSpaceOnUse"><stop class="jhl5_6blw"/><stop offset=".22" class="n0z3adckj"/><stop offset=".45" class="rvmki439c"/><stop offset=".71" class="ozzad3bdh"/><stop offset="1" class="gphtemtom"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:ubt" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.gphtemtom) {
  stop-color: var(--svg-color--da1e74, #da1e74);
}

:global(.iop1w-k-p) {
  d: path("M21 5.25L18.75 3h-9v14.625H6.375V5.25H3v13.5L5.25 21h5.625l2.25-2.25h5.625L21 16.5V12l-1.125-1.125L21 9.75zm-7.875 1.125h4.5V9.75h-4.5zm4.5 9h-4.5V12h4.5z");
}

:global(.jhl5_6blw) {
  stop-color: var(--svg-color--f5e710, #f5e710);
}

:global(.n0z3adckj) {
  stop-color: var(--svg-color--4db15a, #4db15a);
}

:global(.ozzad3bdh) {
  stop-color: var(--svg-color--1e548a, #1e548a);
}

:global(.rvmki439c) {
  stop-color: var(--svg-color--00a09a, #00a09a);
}

</style>
