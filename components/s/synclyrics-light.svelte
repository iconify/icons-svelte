<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isigbcz0e.css';
import '../../css/s/smxa6kc9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="isigbcz0e"/><path class="smxa6kc9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synclyrics-light" {...props}></Icon>
