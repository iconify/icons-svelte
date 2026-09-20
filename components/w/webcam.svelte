<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/rtin43b5w.css';
import '../../css/y/ywyzcbcrm.css';
import '../../css/r/ry84oklno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="rtin43b5w"/><path class="ywyzcbcrm"/><path class="ry84oklno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:webcam" {...props}></Icon>
