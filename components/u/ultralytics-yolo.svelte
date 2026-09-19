<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wngs4vr5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wngs4vr5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:ultralytics-yolo" {...props}></Icon>
