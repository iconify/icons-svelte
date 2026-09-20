<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtq_hhlkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rtq_hhlkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zot-registry-dark" {...props}></Icon>
