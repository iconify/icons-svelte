<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaru8kblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qaru8kblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visible-by-verizon-dark" {...props}></Icon>
