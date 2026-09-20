<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gjy1piopn"><path class="pr2rzkb1v"/><path class="fvsaf-g0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:xor" {...props}></Icon>
<style>
:global(.fvsaf-g0e) {
  d: path("M6.375 12v-1.687h5.063V9.187H6.375V7.5h11.25v1.687h-5.062v1.126h5.062V12h-4.882l4.778 7.109A9 9 0 0 0 21 12a9 9 0 0 0-9-9a9 9 0 0 0-5.522 16.109L11.258 12z");
}

:global(.gjy1piopn) {
  fill: var(--svg-color--e3232c, #e3232c);
}

:global(.pr2rzkb1v) {
  d: path("M7.715 19.914A8.94 8.94 0 0 0 12 21a8.94 8.94 0 0 0 4.284-1.086L12 13.532z");
}

</style>
