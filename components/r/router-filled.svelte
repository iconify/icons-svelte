<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d41t4hb4s.css';
import '../../css/q/qm5nf-7wy.css';
import '../../css/k/k6pdl9s_w.css';
import '../../css/p/p5n3zo29p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d41t4hb4s"/><path class="qm5nf-7wy"/><path class="k6pdl9s_w"/><path clip-rule="evenodd" class="p5n3zo29p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:router-filled" {...props}></Icon>
