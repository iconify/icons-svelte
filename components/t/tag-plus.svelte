<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/y3nvxmjsp.css';
import '../../css/g/gsv_mxbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="y3nvxmjsp"/><path class="gsv_mxbid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-plus" {...props}></Icon>
