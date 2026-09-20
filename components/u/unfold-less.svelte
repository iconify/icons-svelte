<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti4n6cxcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti4n6cxcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:unfold-less" {...props}></Icon>
