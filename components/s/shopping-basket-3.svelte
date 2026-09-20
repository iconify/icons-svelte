<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxa1xlbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxa1xlbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:shopping-basket-3" {...props}></Icon>
