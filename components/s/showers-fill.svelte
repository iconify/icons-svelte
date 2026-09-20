<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrnbmrbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrnbmrbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:showers-fill" {...props}></Icon>
