<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo1eldb9g.css';
import '../../css/e/e26qy--yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fo1eldb9g"/><path class="e26qy--yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-inverter-20" {...props}></Icon>
