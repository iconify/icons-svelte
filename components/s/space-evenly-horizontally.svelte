<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy0s6l-yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iy0s6l-yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:space-evenly-horizontally" {...props}></Icon>
