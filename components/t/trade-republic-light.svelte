<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr_hn414m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wr_hn414m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trade-republic-light" {...props}></Icon>
