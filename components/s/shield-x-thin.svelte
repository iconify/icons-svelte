<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evmif1bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="evmif1bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:shield-x-thin" {...props}></Icon>
