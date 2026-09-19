<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8z9413sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":272,"height":432};
const content = `<path class="p8z9413sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tumblr" {...props}></Icon>
