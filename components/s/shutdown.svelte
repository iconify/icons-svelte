<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_s4zp7_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h_s4zp7_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:shutdown" {...props}></Icon>
