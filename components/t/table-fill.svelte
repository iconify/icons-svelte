<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="crihq1b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:table-fill" {...props}></Icon>
<style>
:global(.crihq1b9u) {
  fill: currentColor;
  d: path("M224 48H32a8 8 0 0 0-8 8v136a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V56a8 8 0 0 0-8-8M40 112h40v32H40Zm56 0h120v32H96Zm-56 48h40v32H40Zm176 32H96v-32h120z");
}

</style>
