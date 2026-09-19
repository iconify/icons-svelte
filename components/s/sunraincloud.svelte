<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk6vu-bip.css';
import '../../css/i/i_urbac4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="vk6vu-bip"/><path class="i_urbac4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:sunraincloud" {...props}></Icon>
