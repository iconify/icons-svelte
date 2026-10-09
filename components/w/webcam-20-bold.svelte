<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0vq58ann.css';
import '../../css/s/szrxxwb4q.css';
import '../../css/e/e4o8tz19x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u0vq58ann"/><path class="szrxxwb4q"/><path class="e4o8tz19x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:webcam-20-bold" {...props}></Icon>
