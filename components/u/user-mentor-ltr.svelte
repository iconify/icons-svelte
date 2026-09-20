<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll2zbfrsu.css';
import '../../css/c/chmm2dpgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ll2zbfrsu"/><circle class="chmm2dpgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-mentor-ltr" {...props}></Icon>
