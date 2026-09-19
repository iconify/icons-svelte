<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4l5a2vcw.css';
import '../../css/h/h40gxbcln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a4l5a2vcw"/><path class="h40gxbcln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:task" {...props}></Icon>
