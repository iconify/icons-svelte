<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="moacmzb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:yellow-circle" {...props}></Icon>
<style>
:global(.moacmzb6j) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--fdcb58, #fdcb58);
}

</style>
