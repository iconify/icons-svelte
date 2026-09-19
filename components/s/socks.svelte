<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5ri8ny9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j5ri8ny9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:socks" {...props}></Icon>
