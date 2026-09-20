<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixtp24b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ixtp24b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:verizon-light" {...props}></Icon>
