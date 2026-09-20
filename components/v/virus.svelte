<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e2kadjbvp.css';
import '../../css/x/xqhdghbln.css';
import '../../css/u/uxzt8-b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="e2kadjbvp"/><path class="xqhdghbln"/><path clip-rule="evenodd" class="uxzt8-b9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:virus" {...props}></Icon>
