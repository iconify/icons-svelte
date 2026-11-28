<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh0k4frur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh0k4frur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:user-circle-info" {...props}></Icon>
