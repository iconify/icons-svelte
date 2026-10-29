<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v9ome130x.css';
import '../../css/l/ljy9tlj1f.css';
import '../../css/v/vcac4wbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v9ome130x wm-k"/><path class="ljy9tlj1f wm-k"/><path class="vcac4wbmb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:scan-eye-sketch" {...props}></Icon>
