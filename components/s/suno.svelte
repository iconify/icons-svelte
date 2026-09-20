<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc3we9v5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc3we9v5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:suno" {...props}></Icon>
