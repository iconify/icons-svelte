<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb-7heutx.css';
import '../../css/b/bgfe5mgwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yb-7heutx"/><path class="bgfe5mgwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermistor-48-bold" {...props}></Icon>
