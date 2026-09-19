<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g6qerqb0o.css';
import '../../css/u/u_y0o5bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><circle class="g6qerqb0o"/><path class="u_y0o5bpw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:user-solo-fill-12" {...props}></Icon>
