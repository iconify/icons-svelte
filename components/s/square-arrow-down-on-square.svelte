<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9wx0ebay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="e9wx0ebay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-arrow-down-on-square" {...props}></Icon>
