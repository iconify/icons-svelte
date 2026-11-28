<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pwyacq_9t.css';
import '../../css/l/lbixp3wyq.css';
import '../../css/p/pb--brbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pwyacq_9t"/><path class="lbixp3wyq"/><path class="pb--brbnr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:swimmer" {...props}></Icon>
