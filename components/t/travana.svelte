<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="hmy85y4fk"/><circle class="be57hbcse"/><circle class="ibik9ibpb"/><circle class="r_m0-ac_x"/><circle class="t9n2q7b0h"/><circle class="b7oyfv17a"/><circle class="v2ftg1bcz"/><circle class="ci9gh8brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:travana" {...props}></Icon>
<style>
:global(.b7oyfv17a) {
  cx: 35.116px;
  cy: 29.334px;
  r: 3.309px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.be57hbcse) {
  cx: 22.535px;
  cy: 21.662px;
  r: 4.768px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ci9gh8brp) {
  cx: 25.905px;
  cy: 10.94px;
  r: 3.878px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.hmy85y4fk) {
  cx: 24.617px;
  cy: 35.794px;
  r: 6.307px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ibik9ibpb) {
  cx: 37.751px;
  cy: 18.569px;
  r: 4.768px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.r_m0-ac_x) {
  cx: 9.869px;
  cy: 39.113px;
  r: 4.387px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.t9n2q7b0h) {
  cx: 12.619px;
  cy: 28.552px;
  r: 3.309px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.v2ftg1bcz) {
  cx: 36.615px;
  cy: 7.511px;
  r: 3.011px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
