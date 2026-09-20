<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb0r06b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fb0r06b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:step-forward" {...props}></Icon>
