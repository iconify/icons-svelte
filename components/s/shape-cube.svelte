<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b_kv34bwu.css';
import '../../css/v/vbno8kv6y.css';
import '../../css/h/hsnp8gqct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b_kv34bwu"/><path class="vbno8kv6y"/><path class="hsnp8gqct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:shape-cube" {...props}></Icon>
