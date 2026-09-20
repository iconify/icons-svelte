<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp1zz_b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp1zz_b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:solana-sol-line" {...props}></Icon>
