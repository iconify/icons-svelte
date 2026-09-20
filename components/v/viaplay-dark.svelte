<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6ghiig2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q6ghiig2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:viaplay-dark" {...props}></Icon>
