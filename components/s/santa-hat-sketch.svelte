<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gjvqajwca.css';
import '../../css/y/y5j9z9byl.css';
import '../../css/z/zuj_ibfbz.css';
import '../../css/k/kck4_gd1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gjvqajwca"/><path class="wm-k y5j9z9byl"/><path class="wm-k zuj_ibfbz"/><path class="kck4_gd1h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:santa-hat-sketch" {...props}></Icon>
