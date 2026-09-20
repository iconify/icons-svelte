<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcf0u5b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kcf0u5b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:socket-io-dark" {...props}></Icon>
