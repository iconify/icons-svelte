<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn_kxoijr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pn_kxoijr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:stethoscope" {...props}></Icon>
