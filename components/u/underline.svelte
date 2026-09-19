<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7-5tc2vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i7-5tc2vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:underline" {...props}></Icon>
