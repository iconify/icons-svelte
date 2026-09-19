<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwy7sxrzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1280};
const content = `<path class="jwy7sxrzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:video-camera" {...props}></Icon>
