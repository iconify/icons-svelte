<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kr9nmynla.css';
import '../../css/p/pcsn_fbse.css';
import '../../css/l/ldyoqd6ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="kr9nmynla"/><path class="pcsn_fbse"/><path class="ldyoqd6ke"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:soft-drink" {...props}></Icon>
