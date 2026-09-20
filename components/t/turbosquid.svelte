<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoc3d92or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoc3d92or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:turbosquid" {...props}></Icon>
