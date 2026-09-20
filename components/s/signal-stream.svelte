<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tobmkjx4s.css';
import '../../css/b/bb602ybpl.css';
import '../../css/o/o-ezxobzr.css';
import '../../css/o/oc5c_p17s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tobmkjx4s"/><path clip-rule="evenodd" class="bb602ybpl"/><path class="o-ezxobzr"/><path class="oc5c_p17s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:signal-stream" {...props}></Icon>
