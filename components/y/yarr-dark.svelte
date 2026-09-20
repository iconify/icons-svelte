<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9el3bc1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s9el3bc1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yarr-dark" {...props}></Icon>
