<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fdjvl4ufq"/><path class="kedsvqbax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trending-down" {...props}></Icon>
<style>
:global(.fdjvl4ufq) {
  d: path("m2.75 6.75l6 6l4-4l8.5 8.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kedsvqbax) {
  d: path("M15.25 17.25h6v-6");
}

</style>
