<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mev08f5hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stapler-mini-sharp" {...props}></Icon>
<style>
:global(.mev08f5hj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6.75h10.75l.97 1.46l.06.08l.97 1.46v2H4.75v-5zm.5 5v3m-3.25 0h16.5v4.5H3.75z");
}

</style>
