<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl5lsw3qs.css';
import '../../css/z/zzcp-vb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cl5lsw3qs"/><path class="zzcp-vb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ticket" {...props}></Icon>
