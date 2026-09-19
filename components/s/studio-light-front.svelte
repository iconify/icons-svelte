<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vx5xd6byq.css';
import '../../css/q/qe5mrybjn.css';
import '../../css/j/j9yh9hwkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="vx5xd6byq"/><path class="qe5mrybjn"/><path class="j9yh9hwkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:studio-light-front" {...props}></Icon>
