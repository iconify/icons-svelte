<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/avskq2y1q.css';
import '../../css/f/fhlmw7bsz.css';
import '../../css/q/qr6e_mnfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="avskq2y1q"/><path clip-rule="evenodd" class="fhlmw7bsz"/><path class="qr6e_mnfo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:siren2-filled" {...props}></Icon>
