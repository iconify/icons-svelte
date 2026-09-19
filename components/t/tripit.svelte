<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="c3y9mdbxy"/><circle class="z73wsu4vj"/><circle class="ulvwq6ban"/><ellipse class="g38gf0tjd"/><circle class="kwi3-ib-p"/><path class="hc8hicbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tripit" {...props}></Icon>
<style>
:global(.c3y9mdbxy) {
  cx: 10.666px;
  cy: 27.648px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.166px;
  ry: 5.536px;
}

:global(.g38gf0tjd) {
  cx: 38.516px;
  cy: 27.648px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.984px;
  ry: 4.522px;
}

:global(.hc8hicbwf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.666 22.112v-4.586m4.874 6.737l6.401-4.444m-5.109 7.829h16.7m-13.321 5.953l-4.226-3.159");
}

:global(.kwi3-ib-p) {
  cx: 23.255px;
  cy: 35.51px;
  r: 3.597px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ulvwq6ban) {
  cx: 10.666px;
  cy: 13.21px;
  r: 4.316px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z73wsu4vj) {
  cx: 24.488px;
  cy: 18.04px;
  r: 3.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
