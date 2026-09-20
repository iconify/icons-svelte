<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gb3vtejwz.css';
import '../../css/l/lmfsi8bqv.css';
import '../../css/d/d0l7ov6dg.css';
import '../../css/t/tk78z4b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gb3vtejwz"/><path class="lmfsi8bqv"/><path class="d0l7ov6dg"/><path class="tk78z4b2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-speak-bold" {...props}></Icon>
