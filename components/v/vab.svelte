<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy1d94bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy1d94bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vab" {...props}></Icon>
