<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs_m5qbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs_m5qbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:time" {...props}></Icon>
