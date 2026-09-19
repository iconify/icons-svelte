<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm6b_0xno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pm6b_0xno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:software-resource-cluster" {...props}></Icon>
