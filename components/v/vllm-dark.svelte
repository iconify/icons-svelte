<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7-mx-psp.css';
import '../../css/w/wgujkib2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r7-mx-psp"/><path class="wgujkib2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vllm-dark" {...props}></Icon>
