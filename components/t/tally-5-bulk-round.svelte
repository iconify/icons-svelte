<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw5w_lbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw5w_lbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tally-5-bulk-round" {...props}></Icon>
