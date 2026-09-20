<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip-a2mckl.css';
import '../../css/p/p_p4lxbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ip-a2mckl"/><path class="p_p4lxbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spotify" {...props}></Icon>
