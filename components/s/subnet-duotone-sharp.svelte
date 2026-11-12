<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ewhpjo-tg"/><path class="enf8r70mr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:subnet-duotone-sharp" {...props}></Icon>
<style>
:global(.enf8r70mr) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11h18v10H3Zm7-6a2 2 0 1 0 4 0a2 2 0 0 0-4 0M7 16h.01M12 16h.01M17 16h.01M12 7v4");
}

:global(.ewhpjo-tg) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.236 3.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M22 11v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V11a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1");
}

:global(.ft5dv1b6b) {
  fill: none;
}

</style>
