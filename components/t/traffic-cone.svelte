<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp1c9py_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xp1c9py_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:traffic-cone" {...props}></Icon>
