<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf7n-7b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xf7n-7b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:seedsync-dark" {...props}></Icon>
