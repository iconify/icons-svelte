<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5cg8fb9r.css';
import '../../css/i/iimhfp_bg.css';
import '../../css/x/x92qun6vf.css';
import '../../css/z/zx2accbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y5cg8fb9r"><path class="iimhfp_bg"/><path class="x92qun6vf"/><path class="zx2accbtj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:spinning-top" {...props}></Icon>
