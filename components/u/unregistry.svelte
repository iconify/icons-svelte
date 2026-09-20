<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bltugjkhs.css';
import '../../css/v/vq3qgrprl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bltugjkhs"/><path class="vq3qgrprl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unregistry" {...props}></Icon>
