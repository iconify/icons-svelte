<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnmy-k-kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnmy-k-kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:target-3" {...props}></Icon>
