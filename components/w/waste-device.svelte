<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3wuugj7j.css';
import '../../css/y/ypl2tntwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j3wuugj7j"/><path class="ypl2tntwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:waste-device" {...props}></Icon>
