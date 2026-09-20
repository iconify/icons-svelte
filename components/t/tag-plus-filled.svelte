<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/gsv_mxbid.css';
import '../../css/x/xov4t3bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="gsv_mxbid"/><path class="xov4t3bzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-plus-filled" {...props}></Icon>
