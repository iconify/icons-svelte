<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baq4hj58q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="baq4hj58q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:send-duo" {...props}></Icon>
