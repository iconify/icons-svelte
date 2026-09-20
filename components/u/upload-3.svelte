<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5ja4vb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m5ja4vb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:upload-3" {...props}></Icon>
