<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_tp76blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_tp76blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:solana-sol-line" {...props}></Icon>
