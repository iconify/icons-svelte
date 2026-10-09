<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fram0bcsw.css';
import '../../css/o/oz54tcchs.css';
import '../../css/d/d4o8lobkk.css';
import '../../css/u/ux_xktusc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fram0bcsw"/><path class="oz54tcchs"/><path class="d4o8lobkk"/><path class="ux_xktusc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scales-48-bold" {...props}></Icon>
