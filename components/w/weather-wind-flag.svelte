<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb7uilnfd.css';
import '../../css/a/assurkbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xb7uilnfd"/><path class="assurkbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:weather-wind-flag" {...props}></Icon>
