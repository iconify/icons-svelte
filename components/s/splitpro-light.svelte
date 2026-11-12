<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g58_hc9td.css';
import '../../css/w/wh_63k2aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g58_hc9td"/><path class="wh_63k2aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:splitpro-light" {...props}></Icon>
