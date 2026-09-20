<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/utymdgx_e.css';
import '../../css/x/x1sq-9b4b.css';
import '../../css/c/cfl3_9b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="utymdgx_e"/><path class="x1sq-9b4b"/><path class="cfl3_9b4r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:video-frame-play-horizontal-line-duotone" {...props}></Icon>
