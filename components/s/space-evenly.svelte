<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzgr0_bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:space-evenly" {...props}></Icon>
<style>
:global(.dzgr0_bpj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3v18m19-18v18M7.25 9v6M12 9v6m4.75-6v6");
}

</style>
