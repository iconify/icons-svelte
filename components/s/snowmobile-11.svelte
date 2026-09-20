<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx31-920e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="vx31-920e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:snowmobile-11" {...props}></Icon>
