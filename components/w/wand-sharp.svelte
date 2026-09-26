<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_l3fw_0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wand-sharp" {...props}></Icon>
<style>
:global(.y_l3fw_0j) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.4645 3L21 6.5355L6.5355 21L3 17.4645L17.4645 3ZM13.1251 7.3393L16.6607 10.8749");
}

</style>
