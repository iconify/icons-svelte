<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wl0x9u5jz.css';
import '../../css/o/oud6qo14q.css';
import '../../css/d/disikgarl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wl0x9u5jz"/><path class="oud6qo14q"/><path class="disikgarl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:wifi-router-flat" {...props}></Icon>
