<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvm3lumsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cvm3lumsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xmpp-light" {...props}></Icon>
