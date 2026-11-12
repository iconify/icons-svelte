<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycwaf5q0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ycwaf5q0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:systemd" {...props}></Icon>
