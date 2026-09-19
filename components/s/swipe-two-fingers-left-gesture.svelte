<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3q7pac3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3q7pac3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:swipe-two-fingers-left-gesture" {...props}></Icon>
