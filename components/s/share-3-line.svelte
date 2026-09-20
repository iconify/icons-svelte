<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd64vy-7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd64vy-7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:share-3-line" {...props}></Icon>
