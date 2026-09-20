<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy9np2b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vy9np2b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:screen-smartphone" {...props}></Icon>
