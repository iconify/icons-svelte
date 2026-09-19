<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxts3kbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="jxts3kbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:volume-off" {...props}></Icon>
