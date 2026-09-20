<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy7st-bkc.css';
import '../../css/u/ub4v3ecgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dy7st-bkc"/><path class="ub4v3ecgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tailscale-dark" {...props}></Icon>
