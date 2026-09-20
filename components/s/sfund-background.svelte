<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGNcAllcda)" class="r4i437pya"/><path class="rblv-jbit"/><path class="isuslabre"/></g><defs><linearGradient id="SVGNcAllcda" x1="11.992" x2="11.992" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="p3o77ib8v"/><stop offset="1" class="uzjifdb_b"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:sfund-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.isuslabre) {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.785 20c-1.305-1.204-3.272-4.48-.716-7.966l.977-1.285c.543-.732 1.221-2.757.021-4.416c-.147-.202-1.133-.889-1.86-.169l-.094.105l.093-.1L12.172 4c1.335 1.187 3.403 4.37.998 7.608l-1.263 1.634c-.459.653-1.107 2.484 0 4.615c.257.387 1.263.598 2.101-.337z");
}

:global(.p3o77ib8v) {
  stop-color: var(--svg-color--986ef8, #986ef8);
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.rblv-jbit) {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.418 7.01l2.78-2.968l.113 1.874c-.413.43-1.747 1.684-3.28 3.697c-1.364 1.79-.055 4.072.943 4.893v1.663c-.653-.354-1.84-.83-2.712-2.981c-1.077-2.653.851-4.666 2.156-6.177m5.234 9.839l-2.787 2.972l-.11-1.873c.413-.434 1.642-1.777 3.284-3.697c1.348-1.583 0-4.148-.943-4.682V7.923c.649.354 1.743.69 2.619 2.842c1.074 2.653-.631 4.876-2.063 6.085");
}

:global(.uzjifdb_b) {
  stop-color: var(--svg-color--4592e6, #4592e6);
}

</style>
