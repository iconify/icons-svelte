<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxdn0e28r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sxdn0e28r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:stats-chart" {...props}></Icon>
