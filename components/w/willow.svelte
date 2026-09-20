<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdfli1b4k.css';
import '../../css/j/j3rnxybvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mdfli1b4k"/><path class="j3rnxybvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:willow" {...props}></Icon>
