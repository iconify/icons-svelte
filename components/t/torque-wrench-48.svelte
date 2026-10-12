<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xywdqfbfw.css';
import '../../css/w/wmfwlabqo.css';
import '../../css/h/hrs6edb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xywdqfbfw"/><path class="wmfwlabqo"/><path class="hrs6edb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:torque-wrench-48" {...props}></Icon>
