<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi60ecbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="hi60ecbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:time-9" {...props}></Icon>
