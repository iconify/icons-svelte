<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9nw32blw.css';
import '../../css/m/m2a5m1fuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w9nw32blw"/><path class="m2a5m1fuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vllm-light" {...props}></Icon>
