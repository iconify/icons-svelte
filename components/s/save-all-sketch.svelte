<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pqg6tsbgc.css';
import '../../css/s/s4j63ro3g.css';
import '../../css/p/pn3iilfqd.css';
import '../../css/u/uo_lw3hck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pqg6tsbgc"/><path class="s4j63ro3g wm-a"/><path class="pn3iilfqd wm-k"/><path class="uo_lw3hck wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:save-all-sketch" {...props}></Icon>
