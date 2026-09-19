<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwy8aw0id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rwy8aw0id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:video-camera-20-solid" {...props}></Icon>
