<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/a/at2izmb5l.css';
import '../../css/l/lvmg8g6js.css';
import '../../css/h/hta33-9ph.css';
import '../../css/p/ps6gdacnv.css';
import '../../css/t/tsa3egbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="at2izmb5l wm-shadow"/><path class="lvmg8g6js wm-shadow"/><path class="hta33-9ph"/><path class="ps6gdacnv"/><path class="tsa3egbgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:thermometer-snowflake" {...props}></Icon>
