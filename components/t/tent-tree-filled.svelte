<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh2aqpbkj.css';
import '../../css/y/ysegc7b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yh2aqpbkj"/><path class="ysegc7b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tent-tree-filled" {...props}></Icon>
