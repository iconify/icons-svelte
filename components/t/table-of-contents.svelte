<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td_0am-yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="td_0am-yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:table-of-contents" {...props}></Icon>
