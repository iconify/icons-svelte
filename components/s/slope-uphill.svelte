<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygt3p0bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygt3p0bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:slope-uphill" {...props}></Icon>
