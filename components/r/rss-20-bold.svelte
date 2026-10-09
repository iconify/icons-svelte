<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0oe2vbzu.css';
import '../../css/z/zijqf-s4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i0oe2vbzu"/><path class="zijqf-s4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rss-20-bold" {...props}></Icon>
