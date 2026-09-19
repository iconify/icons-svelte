<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyu-84h5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xyu-84h5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:stopwatch" {...props}></Icon>
