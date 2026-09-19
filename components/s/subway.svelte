<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m38t_g0lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":408};
const content = `<path class="m38t_g0lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:subway" {...props}></Icon>
