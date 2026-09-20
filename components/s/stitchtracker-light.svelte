<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iou1crsje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iou1crsje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stitchtracker-light" {...props}></Icon>
