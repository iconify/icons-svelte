<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc182sbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wc182sbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sabnzbd-dark" {...props}></Icon>
