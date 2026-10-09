<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkh_084xi.css';
import '../../css/w/wpnm42b6c.css';
import '../../css/g/g17jsq6yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rkh_084xi"/><path class="wpnm42b6c"/><path class="g17jsq6yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-charging-20-bold" {...props}></Icon>
