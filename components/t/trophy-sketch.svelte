<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ih6qqcvxi.css';
import '../../css/c/ckiijib5f.css';
import '../../css/c/ct7tzk2gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ih6qqcvxi"/><path class="ckiijib5f"/><path class="ct7tzk2gs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trophy-sketch" {...props}></Icon>
