<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrnzrzbbr.css';
import '../../css/h/h6m5ozxxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrnzrzbbr"/><path class="h6m5ozxxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smartphone-app-widget-remove" {...props}></Icon>
