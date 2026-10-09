<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxt_aqbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xxt_aqbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-forecast-48-bold" {...props}></Icon>
