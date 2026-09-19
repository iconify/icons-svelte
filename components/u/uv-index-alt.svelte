<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy0u-nfrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xy0u-nfrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:uv-index-alt" {...props}></Icon>
