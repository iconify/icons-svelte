<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg8s0sbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg8s0sbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:watch-fill" {...props}></Icon>
