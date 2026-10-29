<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/ngc7rqivy.css';
import '../../css/t/t8a6dybzk.css';
import '../../css/m/mk4038byc.css';
import '../../css/c/c9ke8ubkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ngc7rqivy wm-k"/><path class="t8a6dybzk wm-a"/><path class="mk4038byc wm-k"/><path class="c9ke8ubkk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:subscript-sketch" {...props}></Icon>
