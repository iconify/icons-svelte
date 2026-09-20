<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx0wwp2tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vx0wwp2tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:stitches-logo" {...props}></Icon>
