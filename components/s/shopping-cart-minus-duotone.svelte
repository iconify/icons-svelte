<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rx7060mtz.css';
import '../../css/g/g8vw4eb5x.css';
import '../../css/d/d_czc4bgz.css';
import '../../css/j/ja581zbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rx7060mtz"/><path class="g8vw4eb5x"/><path class="d_czc4bgz"/><path class="ja581zbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shopping-cart-minus-duotone" {...props}></Icon>
