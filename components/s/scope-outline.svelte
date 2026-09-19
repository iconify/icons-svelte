<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lk35y-bvr.css';
import '../../css/c/cn5-l9bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="scope-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="lk35y-bvr"/><path class="cn5-l9bdz"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:scope-outline" {...props}></Icon>
