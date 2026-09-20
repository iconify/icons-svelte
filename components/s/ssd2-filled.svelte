<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l1ij4_b_p.css';
import '../../css/t/tbkyqd4aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l1ij4_b_p"/><path clip-rule="evenodd" class="tbkyqd4aw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ssd2-filled" {...props}></Icon>
