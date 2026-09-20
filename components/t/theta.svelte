<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGlUr1FH7J)" clip-rule="evenodd" class="sy6kbjfur"/><path fill="url(#SVGh4avr46C)" class="afazy16kv"/><defs><linearGradient id="SVGlUr1FH7J" x1="4.825" x2="19.536" y1="4.355" y2="19.844" gradientUnits="userSpaceOnUse"><stop class="qyx7slpkd"/><stop offset=".53" class="toy1_lbnc"/><stop offset="1" class="hdgq2zblw"/></linearGradient><linearGradient id="SVGh4avr46C" x1="8.413" x2="16.902" y1="7.571" y2="15.291" gradientUnits="userSpaceOnUse"><stop class="qyx7slpkd"/><stop offset=".53" class="toy1_lbnc"/><stop offset="1" class="hdgq2zblw"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:theta" {...props}></Icon>
<style>
:global(.afazy16kv) {
  d: path("M11.527 9.628H9.158v.948h5.684v-.948h-2.368V6.786h-.947zm0 4.737H9.158v-.947h5.684v.947h-2.368v2.842h-.947z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.hdgq2zblw) {
  stop-color: var(--svg-color--2ee4be, #2ee4be);
}

:global(.qyx7slpkd) {
  stop-color: var(--svg-color--2ab8e6, #2ab8e6);
}

:global(.sy6kbjfur) {
  fill-rule: evenodd;
  d: path("M16.737 3.947H7.263v16.106h9.474zm-10.421 0v16.106l.947.947h9.474l.947-.947V3.947L16.737 3H7.263z");
}

:global(.toy1_lbnc) {
  stop-color: var(--svg-color--29cad2, #29cad2);
}

</style>
