<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plzz2p7cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plzz2p7cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:usb-x" {...props}></Icon>
