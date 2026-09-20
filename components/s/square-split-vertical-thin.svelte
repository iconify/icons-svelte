<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="q-cshf5sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:square-split-vertical-thin" {...props}></Icon>
<style>
:global(.q-cshf5sf) {
  fill: currentColor;
  d: path("M200 44H56a12 12 0 0 0-12 12v144a12 12 0 0 0 12 12h144a12 12 0 0 0 12-12V56a12 12 0 0 0-12-12M56 52h144a4 4 0 0 1 4 4v68H52V56a4 4 0 0 1 4-4m144 152H56a4 4 0 0 1-4-4v-68h152v68a4 4 0 0 1-4 4");
}

</style>
