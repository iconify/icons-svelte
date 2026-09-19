<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyad3pbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wyad3pbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:splotch" {...props}></Icon>
