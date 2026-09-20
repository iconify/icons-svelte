<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e38ojchyh.css';
import '../../css/c/c24svnd2a.css';
import '../../css/d/d1s63ybjv.css';
import '../../css/g/gvp4ae15o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e38ojchyh"/><path class="c24svnd2a"/><circle class="d1s63ybjv"/><circle class="gvp4ae15o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:text-tool-filled" {...props}></Icon>
