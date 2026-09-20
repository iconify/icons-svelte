<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xt2k4r6vg.css';
import '../../css/x/xvkvswr6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xt2k4r6vg"/><path class="xvkvswr6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:scanner-bar-code-flat" {...props}></Icon>
