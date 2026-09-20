<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fon-ibcks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fon-ibcks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:whatsapp-light" {...props}></Icon>
