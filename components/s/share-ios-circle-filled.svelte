<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG96u13csQ"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="nb1587ngy"/><path class="l97nbfb1i"/><path class="ht9l33ble"/></g></mask></defs><circle mask="url(#SVG96u13csQ)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:share-ios-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ht9l33ble) {
  d: path("M12.36 5.768a1 1 0 1 1 1.28-1.536l3 2.5a1 1 0 1 1-1.28 1.536zM16 12a1 1 0 1 1 0-2h1c1.623 0 3 1.165 3 2.692v7.616C20 21.835 18.623 23 17 23H9c-1.623 0-3-1.165-3-2.692v-7.616C6 11.165 7.377 10 9 10h1a1 1 0 0 1 0 2H9c-.586 0-1 .35-1 .692v7.616c0 .342.414.692 1 .692h8c.586 0 1-.35 1-.692v-7.616c0-.342-.414-.692-1-.692z");
}

:global(.ivjvz2eii) {
  fill: var(--svg-color--000, #000);
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

:global(.l97nbfb1i) {
  d: path("M13.64 5.768a1 1 0 1 0-1.28-1.536l-3 2.5a1 1 0 0 0 1.28 1.536z");
}

:global(.nb1587ngy) {
  d: path("M12 6a1 1 0 0 1 2 0v10.5a1 1 0 1 1-2 0z");
}

</style>
