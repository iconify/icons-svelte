<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ooa16o-xd"/><path class="p8buz1t1r"/><path class="vniunubej"/><path class="g1gntlbfm"/><path class="rwge04jxw"/><path class="g7akhoeoj"/><path class="wlp3ibbib"/><path class="qrqk-5btd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wardrobe-sort-duotone-thin" {...props}></Icon>
<style>
:global(.g1gntlbfm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 17 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g7akhoeoj) {
  d: path("m6 13 6 -6 6 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ooa16o-xd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4c1.5 0 1.5 2 0 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p8buz1t1r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 13 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qrqk-5btd) {
  d: path("m9 17 3 3 3 -3");
}

:global(.rwge04jxw) {
  d: path("M12 4c1.5 0 1.5 2 0 2.5");
}

:global(.vniunubej) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wlp3ibbib) {
  d: path("M6 13h12");
}

</style>
