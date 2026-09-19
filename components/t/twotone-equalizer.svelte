<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvx1lebqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-equalizer" {...props}></Icon>
<style>
:global(.tvx1lebqh) {
  fill: currentColor;
  d: path("M16 9h4v11h-4zm-6-5h4v16h-4zm-6 8h4v8H4z");
}

</style>
