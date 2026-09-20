<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew4z5r.css';
import '../../css/d/d-z279dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew4z5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:weather-cloudy-loop" {...props}></Icon>
