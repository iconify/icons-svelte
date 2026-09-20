<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdexnxz5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdexnxz5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-four-points-box" {...props}></Icon>
