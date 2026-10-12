<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="k_60eybdg"/><path class="m94_6bcvd"/><circle class="nca05cbxo"/><circle class="j8b717y3r"/><path class="s8k3hhbca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:zero-gravity-sharp" {...props}></Icon>
<style>
:global(.j8b717y3r) {
  cx: 18.75px;
  cy: 4.5px;
  r: 1.25px;
}

:global(.k_60eybdg) {
  cx: 12px;
  cy: 9.75px;
  r: 5px;
}

:global(.m94_6bcvd) {
  d: path("M4.95 7.18a7.5 7.5 0 0 1 3.3-3.93m10.8 9.07a7.5 7.5 0 0 1-3.3 3.93");
}

:global(.nca05cbxo) {
  cx: 5.25px;
  cy: 15.5px;
  r: 1.25px;
}

:global(.s8k3hhbca) {
  d: path("M9.25 21.25h5.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
