<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2pxpwk4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2pxpwk4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tv-off" {...props}></Icon>
