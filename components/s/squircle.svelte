<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jum3tqgyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:squircle" {...props}></Icon>
<style>
:global(.jum3tqgyk) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q6.686 0 8.468 1.782T22.25 12t-1.782 8.468T12 22.25t-8.468-1.782T1.75 12t1.782-8.468T12 1.75");
}

</style>
