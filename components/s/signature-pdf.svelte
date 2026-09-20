<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhktnebyi.css';
import '../../css/x/x3okx1b0y.css';
import '../../css/w/wkj5pkqok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yhktnebyi"/><path class="x3okx1b0y"/><path class="wkj5pkqok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:signature-pdf" {...props}></Icon>
