<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1h-1wb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l1h-1wb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:venus-double" {...props}></Icon>
