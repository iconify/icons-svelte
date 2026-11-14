<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcxvetbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shelf-label-wrong" {...props}></Icon>
<style>
:global(.tcxvetbgr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19V7h-19Zm10.1 17H5.5V7h13v6.6M8.5 11H13m-4.5 3.5h3m3.5.5l6 6m0-6l-6 6");
}

</style>
