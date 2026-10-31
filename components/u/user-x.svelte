<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/v/vnq981bkn.css';
import '../../css/l/l8q8ovjdk.css';
import '../../css/z/zoh2-g5is.css';
import '../../css/p/paqk5i3rz.css';
import '../../css/h/h7p1vybbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="vnq981bkn wm-shadow"/><path class="l8q8ovjdk wm-shadow"/><path class="zoh2-g5is"/><path class="paqk5i3rz"/><path class="h7p1vybbd wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:user-x" {...props}></Icon>
