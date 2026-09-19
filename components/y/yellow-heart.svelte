<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="v-y8tkbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:yellow-heart" {...props}></Icon>
<style>
:global(.v-y8tkbpg) {
  fill: var(--svg-color--f5ce3e, #f5ce3e);
  d: path("M61.1 18.2c-6.4-17-27.2-9.4-29.1-.9c-2.6-9-22.9-15.7-29.1.9C-4 36.7 29.6 53.3 32 56c2.4-2.2 36-19.6 29.1-37.8");
}

</style>
