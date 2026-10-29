<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vt19b-b7a.css';
import '../../css/x/xm1qpqbof.css';
import '../../css/d/d2omlvbzu.css';
import '../../css/e/eqcaaebyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vt19b-b7a wm-k"/><path class="wm-a xm1qpqbof"/><path class="d2omlvbzu wm-k"/><path class="eqcaaebyw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tennis-sketch" {...props}></Icon>
