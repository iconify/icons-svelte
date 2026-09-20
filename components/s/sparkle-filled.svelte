<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyg283b4l.css';
import '../../css/h/hish2dbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dyg283b4l"/><path class="hish2dbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:sparkle-filled" {...props}></Icon>
