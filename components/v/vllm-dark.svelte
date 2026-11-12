<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh8ll8kmn.css';
import '../../css/w/wgujkib2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fh8ll8kmn"/><path class="wgujkib2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vllm-dark" {...props}></Icon>
