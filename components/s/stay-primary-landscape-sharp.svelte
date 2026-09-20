<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgezz0zyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stay-primary-landscape-sharp" {...props}></Icon>
<style>
:global(.xgezz0zyv) {
  fill: currentColor;
  d: path("M1 19V5h22v14Zm5-2h12V7H6Zm-3 0h1V7H3Zm17 0h1V7h-1ZM3 17V7h1v10Zm17 0V7h1v10Z");
}

</style>
