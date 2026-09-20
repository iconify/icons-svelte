<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ispw56eac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ispw56eac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smartphone-app-widget-add" {...props}></Icon>
