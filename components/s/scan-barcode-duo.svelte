<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mek1j-bvd.css';
import '../../css/l/l9lv5_bcf.css';
import '../../css/x/x8izv9k1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mek1j-bvd wm-a"/><path class="l9lv5_bcf"/><path class="wm-a x8izv9k1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:scan-barcode-duo" {...props}></Icon>
