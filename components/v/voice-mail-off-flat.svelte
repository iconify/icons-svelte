<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/otrz1n7pe.css';
import '../../css/x/xhvyj69ys.css';
import '../../css/j/jvd558cyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="otrz1n7pe"/><path class="xhvyj69ys"/><path class="jvd558cyr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:voice-mail-off-flat" {...props}></Icon>
