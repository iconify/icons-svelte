<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztrv4pb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ztrv4pb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:text-wrap-light" {...props}></Icon>
