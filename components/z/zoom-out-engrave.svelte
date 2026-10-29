<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h0-4gxbze.css';
import '../../css/j/jv-5mvs8v.css';
import '../../css/f/ff6q2eboe.css';
import '../../css/o/olgj5xbvl.css';
import '../../css/f/fmfz-mbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h0-4gxbze wm-k"/><path class="jv-5mvs8v wm-a"/><path class="ff6q2eboe wm-shadow"/><path class="olgj5xbvl wm-k"/><path class="fmfz-mbie wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:zoom-out-engrave" {...props}></Icon>
