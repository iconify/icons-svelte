<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyuy1bbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fyuy1bbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:superpowers" {...props}></Icon>
