<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fkib5fbzb.css';
import '../../css/n/nplj_bcal.css';
import '../../css/s/sajyvl67j.css';
import '../../css/l/lg35ukd_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fkib5fbzb"/><path class="nplj_bcal wm-k"/><path class="sajyvl67j wm-k"/><path class="lg35ukd_q wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tombstone-sketch" {...props}></Icon>
