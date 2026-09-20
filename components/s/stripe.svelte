<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhz5ljcbr.css';
import '../../css/w/wees9lb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hhz5ljcbr"/><path class="wees9lb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stripe" {...props}></Icon>
