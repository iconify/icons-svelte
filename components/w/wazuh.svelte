<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he3q-t8yh.css';
import '../../css/a/atcx61-tl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="he3q-t8yh"/><circle class="atcx61-tl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wazuh" {...props}></Icon>
