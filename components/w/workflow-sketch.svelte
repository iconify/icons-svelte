<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rmq984bjk.css';
import '../../css/y/y051bxb0l.css';
import '../../css/f/fjzjs9b3x.css';
import '../../css/p/psa_3hb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rmq984bjk"/><path class="wm-k y051bxb0l"/><path class="fjzjs9b3x wm-k"/><path class="psa_3hb6w wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:workflow-sketch" {...props}></Icon>
