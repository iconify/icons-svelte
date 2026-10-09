<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_c06qbpz.css';
import '../../css/j/jb0sdb0ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f_c06qbpz"/><path class="jb0sdb0ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-battery-20" {...props}></Icon>
