<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n28fdybxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n28fdybxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vuetorrent-dark" {...props}></Icon>
