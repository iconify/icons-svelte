<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hddprfk1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hddprfk1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shapes-20" {...props}></Icon>
