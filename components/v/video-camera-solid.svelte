<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lkcvmf63g.css';
import '../../css/m/m0-rokbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="lkcvmf63g"/><path class="m0-rokbhg wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:video-camera-solid" {...props}></Icon>
