<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rrjakbcym.css';
import '../../css/a/a6ca1bcxc.css';
import '../../css/e/epyd8hb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rrjakbcym"/><path class="a6ca1bcxc"/><path class="epyd8hb_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:ui-phone-slider-vertical" {...props}></Icon>
