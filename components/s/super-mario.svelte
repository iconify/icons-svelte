<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vdl_oacln.css';
import '../../css/a/a21aejbzt.css';
import '../../css/d/dkiuhbb3a.css';
import '../../css/o/ol4634bna.css';
import '../../css/o/oqwhjwboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vdl_oacln"/><path class="a21aejbzt"/><path class="dkiuhbb3a"/><path class="ol4634bna"/><path class="oqwhjwboa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:super-mario" {...props}></Icon>
