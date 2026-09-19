<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm-s7t9sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="rm-s7t9sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:upright" {...props}></Icon>
