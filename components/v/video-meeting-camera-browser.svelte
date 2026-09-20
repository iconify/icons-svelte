<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/t/t2ru60cbr.css';
import '../../css/k/kccg3k40n.css';
import '../../css/c/cg5b7tbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="t2ru60cbr"/><path class="kccg3k40n"/><path class="cg5b7tbik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:video-meeting-camera-browser" {...props}></Icon>
