<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugyn5xbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ugyn5xbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:webcam" {...props}></Icon>
