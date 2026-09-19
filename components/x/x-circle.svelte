<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd1444p2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd1444p2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:x-circle" {...props}></Icon>
