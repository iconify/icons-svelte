<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cti6nxbgy.css';
import '../../css/k/kiyzhcvkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cti6nxbgy"/><path class="kiyzhcvkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:webcam-2-bold" {...props}></Icon>
