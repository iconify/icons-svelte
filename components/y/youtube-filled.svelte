<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9oz41bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u9oz41bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:youtube-filled" {...props}></Icon>
