<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wknanbbjf.css';
import '../../css/x/x9hbbzbwd.css';
import '../../css/s/sz0mrrb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<g class="cuyn6tgcc"><path class="wknanbbjf"/><circle class="x9hbbzbwd"/><path class="sz0mrrb6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:universal-access" {...props}></Icon>
