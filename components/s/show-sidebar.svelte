<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccm_eobhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ccm_eobhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:show-sidebar" {...props}></Icon>
