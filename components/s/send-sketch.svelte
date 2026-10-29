<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n3aa3iv0a.css';
import '../../css/d/d7ut18bbg.css';
import '../../css/u/uf0ekee7e.css';
import '../../css/k/k1kj1iruv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n3aa3iv0a"/><path class="d7ut18bbg wm-k"/><path class="uf0ekee7e wm-k"/><path class="k1kj1iruv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:send-sketch" {...props}></Icon>
