<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/ze_-zp_7l.css';
import '../../css/c/csum4n-2b.css';
import '../../css/f/fvpfrkbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ze_-zp_7l"/><path class="csum4n-2b"/><path class="fvpfrkbjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:screen-share-off" {...props}></Icon>
