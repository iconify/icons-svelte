<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjdrzdbgw.css';
import '../../css/z/z03o25o3p.css';
import '../../css/l/lrp9thb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pjdrzdbgw"/><path class="z03o25o3p"/><path class="lrp9thb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:touch-2-filled" {...props}></Icon>
