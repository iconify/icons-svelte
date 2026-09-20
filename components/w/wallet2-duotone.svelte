<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nir5_sbal.css';
import '../../css/s/spmundq3k.css';
import '../../css/w/wd5g6kh7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nir5_sbal"/><path clip-rule="evenodd" class="spmundq3k"/><path class="wd5g6kh7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wallet2-duotone" {...props}></Icon>
