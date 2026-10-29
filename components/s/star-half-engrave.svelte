<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ear-jyb3q.css';
import '../../css/n/n_hj9vbnd.css';
import '../../css/o/om32tosyu.css';
import '../../css/k/k2m212bgo.css';
import '../../css/q/qfd-q7blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ear-jyb3q wm-k"/><path class="n_hj9vbnd wm-a"/><path class="om32tosyu wm-shadow"/><path class="k2m212bgo wm-k"/><path class="qfd-q7blm wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:star-half-engrave" {...props}></Icon>
