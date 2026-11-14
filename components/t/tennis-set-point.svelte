<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ex_wp-xyk"/><path class="c2hqtqrfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tennis-set-point" {...props}></Icon>
<style>
:global(.c2hqtqrfm) {
  d: path("m2.5 11.5l2.5-6l2.25 6l2.5-6l2.5 6");
}

:global(.ex_wp-xyk) {
  d: path("M2.5 5.5v13m9.75-13v13M2.5 5.5h9.75v6H2.5ZM15 15.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
