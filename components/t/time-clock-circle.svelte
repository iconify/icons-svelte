<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzv2ytcnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzv2ytcnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:time-clock-circle" {...props}></Icon>
