<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4c96bbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="k4c96bbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-js" {...props}></Icon>
