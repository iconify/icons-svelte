<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pkw_vuvwi.css';
import '../../css/t/t09_pz2-q.css';
import '../../css/m/mgjs6b63c.css';
import '../../css/c/c4_v7i59t.css';
import '../../css/o/o8mkkgbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pkw_vuvwi wm-k"/><path class="t09_pz2-q wm-a"/><path class="mgjs6b63c wm-shadow"/><path class="c4_v7i59t wm-k"/><path class="o8mkkgbix wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sticky-note-engrave" {...props}></Icon>
