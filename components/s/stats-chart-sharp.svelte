<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvfduderi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rvfduderi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:stats-chart-sharp" {...props}></Icon>
