<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qbvzs6big.css';
import '../../css/m/mv2vj3bqa.css';
import '../../css/i/icg4znpvz.css';
import '../../css/i/i-r457bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qbvzs6big"/><path class="mv2vj3bqa wm-shadow"/><path class="icg4znpvz"/><path class="i-r457bof wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sliders-engrave" {...props}></Icon>
