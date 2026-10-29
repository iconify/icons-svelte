<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mgtat_gjh.css';
import '../../css/p/pfba09bub.css';
import '../../css/v/vo34gabtt.css';
import '../../css/p/pxcylebuj.css';
import '../../css/s/sl7siidbt.css';
import '../../css/z/z4fg99pfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mgtat_gjh wm-k"/><path class="pfba09bub wm-s"/><path class="vo34gabtt wm-shadow"/><path class="pxcylebuj wm-k"/><path class="sl7siidbt wm-a"/><path class="wm-s z4fg99pfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:smile-plus-engrave" {...props}></Icon>
