<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/db4y25bpl.css';
import '../../css/w/ws80tf5yb.css';
import '../../css/r/rpdqoma1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="db4y25bpl"/><path class="wm-k ws80tf5yb"/><path class="rpdqoma1e wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sun-dim-sketch" {...props}></Icon>
