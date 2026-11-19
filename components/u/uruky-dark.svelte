<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw5ws-b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nw5ws-b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uruky-dark" {...props}></Icon>
