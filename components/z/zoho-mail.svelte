<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpie12blh.css';
import '../../css/w/w092a3gwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tpie12blh"/><path class="w092a3gwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zoho-mail" {...props}></Icon>
