<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjw_gbcgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjw_gbcgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stopwatch-2-line" {...props}></Icon>
