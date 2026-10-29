<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/aykbejljt.css';
import '../../css/v/vd-u-mbdv.css';
import '../../css/g/g73p47bsz.css';
import '../../css/y/y7zzpobdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="aykbejljt"/><path class="vd-u-mbdv wm-a"/><path class="g73p47bsz wm-k"/><path class="wm-a y7zzpobdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:unlock-sketch" {...props}></Icon>
