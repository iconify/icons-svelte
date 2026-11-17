<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwv2d3bhh.css';
import '../../css/l/lrqqa_b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zwv2d3bhh"/><path class="lrqqa_b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vpn-sentinel-dark" {...props}></Icon>
