<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zs1djybzo.css';
import '../../css/n/nm1t5obly.css';
import '../../css/g/gs4hihbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="zs1djybzo"/><path class="nm1t5obly"/><path class="gs4hihbsw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:wordpress" {...props}></Icon>
