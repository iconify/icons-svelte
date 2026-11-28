<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5-m-cc0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x5-m-cc0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:stack-simple-plus-light" {...props}></Icon>
