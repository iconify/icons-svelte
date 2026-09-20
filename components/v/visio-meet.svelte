<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmxtxk5go.css';
import '../../css/o/ofbjwwbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xmxtxk5go"/><path class="ofbjwwbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visio-meet" {...props}></Icon>
