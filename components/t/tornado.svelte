<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0bqxfgrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="l0bqxfgrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tornado" {...props}></Icon>
