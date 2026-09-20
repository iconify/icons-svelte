<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqjreok_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qqjreok_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:speedtest-dark" {...props}></Icon>
