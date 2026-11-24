<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi3b2p9eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi3b2p9eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:wine-off-filled" {...props}></Icon>
