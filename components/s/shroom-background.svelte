<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c1vkhtz-c"/><path clip-rule="evenodd" class="qhn8vjbqz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:shroom-background" {...props}></Icon>
<style>
:global(.c1vkhtz-c) {
  fill: var(--svg-color--a1f931, #a1f931);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.qhn8vjbqz) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("m8.808 14.167l2.251-8.603c-1.084-.229-3.434.023-4.455 3.066c-.938 2.799.965 5.14 2.204 5.537m6.384-4.333l-2.251 8.603c1.084.228 3.434-.024 4.455-3.067c.938-2.799-.965-5.14-2.204-5.536M19.02 9.5h-7.961c.808-3.313 2.93-4.045 3.888-3.998H20zm-6.079 5H4.98L4 18.498h5.052c.96.048 3.08-.685 3.889-3.998");
}

</style>
