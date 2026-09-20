<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lgpgr1b-v"/><path class="pcazvbz0b"/><path class="hdqfcmb-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:wagmigames" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.hdqfcmb-d) {
  fill: var(--svg-color--fd124d, #fd124d);
  d: path("M6.177 8.293v.53h4.114l.339-.287h7.194v-.243z");
}

:global(.lgpgr1b-v) {
  fill: var(--svg-color--00d8ff, #00d8ff);
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m0-1.059a7.942 7.942 0 1 0 0-15.883a7.942 7.942 0 0 0 0 15.883");
}

:global(.pcazvbz0b) {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.379 9.882H6.177l2.838 6.353h.868l2.134-4.844l2.085 4.844h.948l2.774-6.353h-1.133L14.574 14.7l-2.097-4.818h-.9L9.423 14.7l-2.05-4.818z");
}

</style>
