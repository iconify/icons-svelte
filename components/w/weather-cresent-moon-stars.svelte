<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzn1vy6ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rzn1vy6ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:weather-cresent-moon-stars" {...props}></Icon>
