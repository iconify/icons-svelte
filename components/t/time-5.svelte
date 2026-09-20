<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1jvchi8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="q1jvchi8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:time-5" {...props}></Icon>
