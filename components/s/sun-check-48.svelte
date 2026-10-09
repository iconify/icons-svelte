<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrpvxrlxf.css';
import '../../css/p/py4nxfbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vrpvxrlxf"/><path class="py4nxfbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-check-48" {...props}></Icon>
