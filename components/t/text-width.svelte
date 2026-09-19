<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3fnezkjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="l3fnezkjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:text-width" {...props}></Icon>
