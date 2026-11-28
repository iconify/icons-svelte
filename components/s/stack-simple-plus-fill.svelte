<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7up64-ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="z7up64-ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:stack-simple-plus-fill" {...props}></Icon>
