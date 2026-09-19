<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysq1xfblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ysq1xfblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:spray-can-sparkles" {...props}></Icon>
