<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckfbvlb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ckfbvlb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:user-slash-fill" {...props}></Icon>
