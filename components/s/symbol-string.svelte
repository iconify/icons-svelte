<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b211mtdde.css';
import '../../css/o/of28um4lw.css';
import '../../css/w/wfvim_bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="b211mtdde"/><path class="of28um4lw"/><path clip-rule="evenodd" class="wfvim_bfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-string" {...props}></Icon>
