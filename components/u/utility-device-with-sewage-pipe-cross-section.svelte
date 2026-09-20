<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_dkf0bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z_dkf0bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-device-with-sewage-pipe-cross-section" {...props}></Icon>
