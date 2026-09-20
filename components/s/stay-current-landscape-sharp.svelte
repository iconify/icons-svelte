<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkl080bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stay-current-landscape-sharp" {...props}></Icon>
<style>
:global(.dkl080bfi) {
  fill: currentColor;
  d: path("M1 19V5h22v14zm5-2h12V7H6z");
}

</style>
