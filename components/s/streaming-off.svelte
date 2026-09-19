<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzjwq8z-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pzjwq8z-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:streaming-off" {...props}></Icon>
