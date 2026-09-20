<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/lklawe5cz.css';
import '../../css/j/j40labcrn.css';
import '../../css/g/gv3k2ybsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="lklawe5cz"/><rect class="j40labcrn"/><path class="gv3k2ybsd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shapes" {...props}></Icon>
