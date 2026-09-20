<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srd7lnbfg.css';
import '../../css/w/waqnvi5sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="srd7lnbfg"/><path class="waqnvi5sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:trash-can" {...props}></Icon>
