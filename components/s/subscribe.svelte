<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn3v4sbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hn3v4sbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:subscribe" {...props}></Icon>
