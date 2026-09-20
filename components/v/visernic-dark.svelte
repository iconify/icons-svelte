<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpxmj1fbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fpxmj1fbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visernic-dark" {...props}></Icon>
