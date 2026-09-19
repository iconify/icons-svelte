<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/casyzt9mq.css';
import '../../css/p/p-3d8dotc.css';
import '../../css/l/lbj5m-bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="casyzt9mq"><path class="p-3d8dotc"/><path class="lbj5m-bzm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:upload-three" {...props}></Icon>
