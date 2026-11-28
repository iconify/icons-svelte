<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuf1bstzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uuf1bstzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sort-alphabetical-ascending-light" {...props}></Icon>
