<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tm1lnyblt.css';
import '../../css/z/zydpfe68l.css';
import '../../css/w/wzyv2vb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tm1lnyblt"/><path class="zydpfe68l"/><path class="wzyv2vb4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:screwdriver-wrench-flat" {...props}></Icon>
