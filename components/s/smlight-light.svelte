<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_7fzobku.css';
import '../../css/g/gw9s8899s.css';
import '../../css/t/t616afbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="l_7fzobku"/><circle class="gw9s8899s"/><circle class="t616afbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:smlight-light" {...props}></Icon>
