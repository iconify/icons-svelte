<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pk2fqc6zn"/><path class="s_umicbfq"/><path class="sigoiybyx"/><path class="iu3a-_cmb"/><path class="t3v_ptnwp"/><path class="oakk4fbrw"/><path class="ifv_d4f9e"/><path class="d1zyr9bfc"/><path class="iyj_k-bwo"/><path class="jnf_2db5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:runway-duotone-thin" {...props}></Icon>
<style>
:global(.d1zyr9bfc) {
  d: path("M12 4v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ifv_d4f9e) {
  d: path("M17 2v20");
}

:global(.iu3a-_cmb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iyj_k-bwo) {
  d: path("M12 11v4");
}

:global(.jnf_2db5t) {
  d: path("M12 18v3");
}

:global(.oakk4fbrw) {
  d: path("M7 2v20");
}

:global(.pk2fqc6zn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s_umicbfq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sigoiybyx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t3v_ptnwp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 18v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
