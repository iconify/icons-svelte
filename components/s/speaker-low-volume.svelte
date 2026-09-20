<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqogompia.css';
import '../../css/x/xx8n1_bzj.css';
import '../../css/z/z04drlb1l.css';
import '../../css/p/p6bmezxmc.css';
import '../../css/p/p1dxmr8pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="nqogompia"/><path class="xx8n1_bzj"/><g class="z04drlb1l"><path class="p6bmezxmc"/><path class="p1dxmr8pc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:speaker-low-volume" {...props}></Icon>
