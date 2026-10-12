<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rg3c-hb8r.css';
import '../../css/q/qbkn2frqz.css';
import '../../css/d/d2hyv4llv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rg3c-hb8r"/><path class="qbkn2frqz"/><path class="d2hyv4llv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shopping-bag-duotone" {...props}></Icon>
