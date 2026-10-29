<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/ym3gbriop.css';
import '../../css/v/vxxiu3xum.css';
import '../../css/b/b59hop-tj.css';
import '../../css/l/lm0z5rb3y.css';
import '../../css/h/h97q_qbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ym3gbriop"/><path class="vxxiu3xum wm-k"/><path class="b59hop-tj wm-k"/><path class="lm0z5rb3y wm-a"/><path class="h97q_qbxt wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ungroup-sketch" {...props}></Icon>
