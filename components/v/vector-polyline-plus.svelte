<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y91yaib5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y91yaib5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-polyline-plus" {...props}></Icon>
