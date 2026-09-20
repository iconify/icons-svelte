<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mil61zbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mil61zbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tty" {...props}></Icon>
