<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uy525wblg.css';
import '../../css/n/n70p7dbjj.css';
import '../../css/j/jhx07bbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="uy525wblg"/><rect class="n70p7dbjj"/><path class="jhx07bbjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shapes-filled" {...props}></Icon>
