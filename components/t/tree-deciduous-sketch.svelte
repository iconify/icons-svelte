<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m_cnwlbxs.css';
import '../../css/p/pk7vs7bdt.css';
import '../../css/c/cp8-p4b5u.css';
import '../../css/c/cbr2lvb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m_cnwlbxs"/><path class="pk7vs7bdt wm-a"/><path class="cp8-p4b5u wm-k"/><path class="cbr2lvb4c wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tree-deciduous-sketch" {...props}></Icon>
