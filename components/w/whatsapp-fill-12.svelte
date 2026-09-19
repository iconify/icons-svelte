<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxlz_6eqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mxlz_6eqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:whatsapp-fill-12" {...props}></Icon>
