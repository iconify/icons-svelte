<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7iq_fa2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r7iq_fa2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xmpp-dark" {...props}></Icon>
