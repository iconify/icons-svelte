<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkh690d9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:text-append-sharp-fill" {...props}></Icon>
<style>
:global(.fkh690d9e) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 21H22M14 15H22M2 9H22M2 3H22M8.312 21.27L11 18.75L8.284 16.2M11 18.75H3V14");
}

</style>
