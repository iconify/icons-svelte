<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ei557tb3l.css';
import '../../css/a/aolijmb7g.css';
import '../../css/z/zskcxobcc.css';
import '../../css/h/hbl-b_bwz.css';
import '../../css/c/cdq-ahbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ei557tb3l wm-k"/><path class="aolijmb7g wm-a"/><path class="wm-shadow zskcxobcc"/><path class="hbl-b_bwz wm-k"/><path class="cdq-ahbxh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:type-engrave" {...props}></Icon>
