<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx9lulxcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="hx9lulxcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:time-4" {...props}></Icon>
