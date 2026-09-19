<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3c_1v0qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="y3c_1v0qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:snooze-duo" {...props}></Icon>
