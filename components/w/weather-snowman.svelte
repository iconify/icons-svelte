<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev43y730d.css';
import '../../css/y/y-tut6bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ev43y730d"/><path class="y-tut6bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:weather-snowman" {...props}></Icon>
