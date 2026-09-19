<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkhq1rb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kkhq1rb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-nfi" {...props}></Icon>
