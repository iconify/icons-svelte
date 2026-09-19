<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wovc_fb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="wovc_fb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:tumblr-rect" {...props}></Icon>
