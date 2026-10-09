<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc3i7mufd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fc3i7mufd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-forecast-20-bold" {...props}></Icon>
