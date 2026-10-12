<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pwgg57b_h"/><circle class="m_ubk9bxa"/><circle class="npsx14byy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:street-cart-sharp" {...props}></Icon>
<style>
:global(.m_ubk9bxa) {
  cx: 7px;
  cy: 18.75px;
  r: 2.5px;
}

:global(.npsx14byy) {
  cx: 14px;
  cy: 18.75px;
  r: 2.5px;
}

:global(.pwgg57b_h) {
  d: path("M4.5 9.75C5.25 7.25 7.5 6 10.25 6s5 1.25 5.75 3.75Zm-1.5 0h14.5V14H3zM17.5 11l3.75-2");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
