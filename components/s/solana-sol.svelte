<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4hnme9pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4hnme9pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:solana-sol" {...props}></Icon>
