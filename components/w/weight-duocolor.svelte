<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qdy_ubbsn"/><path class="vrnelsbwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:weight-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qdy_ubbsn) {
  stroke-opacity: 0.4;
  d: path("M12 8a2 2 0 1 1 0-4m0 0a2 2 0 1 1 0 4");
}

:global(.vrnelsbwr) {
  d: path("M12 8h3c.882 0 1.706.825 2 2l2 8c.254 1.016-.238 2-1 2H6c-.762 0-1.254-.984-1-2l2-8c.294-1.175 1.118-2 2-2z");
}

</style>
