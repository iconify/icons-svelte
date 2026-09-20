<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sogv6dscv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sogv6dscv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:vectors-anchor-rectangle" {...props}></Icon>
