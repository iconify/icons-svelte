<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="pfg41nwak"/><path class="gdwmsnb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:unlocked" {...props}></Icon>
<style>
:global(.gdwmsnb0w) {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M32 32a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4V18a4 4 0 0 1 4-4h20a4 4 0 0 1 4 4z");
}

:global(.pfg41nwak) {
  fill: var(--svg-color--aab8c2, #aab8c2);
  d: path("M18 0c-4.612 0-8.483 3.126-9.639 7.371l3.855 1.052A6 6 0 0 1 18 4a6 6 0 0 1 6 6v10h4V10c0-5.522-4.477-10-10-10");
}

</style>
