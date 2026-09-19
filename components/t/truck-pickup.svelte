<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_qrfpb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="i_qrfpb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:truck-pickup" {...props}></Icon>
