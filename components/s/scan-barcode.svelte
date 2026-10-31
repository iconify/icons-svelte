<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/u/ults33brt.css';
import '../../css/q/qsbi9kdry.css';
import '../../css/w/wgli4bboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ults33brt wm-shadow"/><path class="qsbi9kdry wm-shadow"/><path class="wgli4bboz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:scan-barcode" {...props}></Icon>
