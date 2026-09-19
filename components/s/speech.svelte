<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxcix4bwn.css';
import '../../css/l/ltk4tpqua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zxcix4bwn"/><path class="ltk4tpqua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:speech" {...props}></Icon>
