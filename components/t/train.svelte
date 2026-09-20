<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6x4_pxoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="k6x4_pxoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:train" {...props}></Icon>
