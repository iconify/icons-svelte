<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fdjvl4ufq"/><path class="kedsvqbax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trending-down-sharp" {...props}></Icon>
<style>
:global(.fdjvl4ufq) {
  d: path("m2.75 6.75l6 6l4-4l8.5 8.5");
}

:global(.kedsvqbax) {
  d: path("M15.25 17.25h6v-6");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
