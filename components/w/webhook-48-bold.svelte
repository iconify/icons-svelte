<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxuzv3bfk.css';
import '../../css/o/oscggibnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sxuzv3bfk"/><path class="oscggibnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:webhook-48-bold" {...props}></Icon>
