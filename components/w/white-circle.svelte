<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="kb8v6gg9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:white-circle" {...props}></Icon>
<style>
:global(.kb8v6gg9n) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--e6e7e8, #e6e7e8);
}

</style>
