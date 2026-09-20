<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo-p5bc0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oo-p5bc0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:weather-moon" {...props}></Icon>
