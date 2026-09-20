<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxr05_b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1227};
const content = `<path class="nxr05_b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:x-formerly-twitter-dark" {...props}></Icon>
