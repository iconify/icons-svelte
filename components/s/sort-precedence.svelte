<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f1_334bfg.css';
import '../../css/n/nb55azqyl.css';
import '../../css/p/puvg98k0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="f1_334bfg"/><path class="nb55azqyl"/><path class="puvg98k0x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:sort-precedence" {...props}></Icon>
