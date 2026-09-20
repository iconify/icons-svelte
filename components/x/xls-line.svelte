<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbbh_ydme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbbh_ydme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:xls-line" {...props}></Icon>
