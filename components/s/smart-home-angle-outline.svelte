<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ix92dhgob.css';
import '../../css/x/xgikp8vnr.css';
import '../../css/l/lupbgxb_z.css';
import '../../css/t/t8828n_8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ix92dhgob"/><path class="xgikp8vnr"/><path class="lupbgxb_z"/><path class="t8828n_8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-home-angle-outline" {...props}></Icon>
