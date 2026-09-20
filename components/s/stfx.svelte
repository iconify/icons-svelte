<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2nf30btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:stfx" {...props}></Icon>
<style>
:global(.a2nf30btz) {
  fill: var(--svg-color--00dd73, #00dd73);
  d: path("m12 4.969l9 14.062H3z");
}

</style>
