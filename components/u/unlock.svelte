<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd4l6dbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd4l6dbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:unlock" {...props}></Icon>
