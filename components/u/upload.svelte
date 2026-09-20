<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmj13wb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmj13wb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:upload" {...props}></Icon>
