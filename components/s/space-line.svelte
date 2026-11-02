<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x14tm3bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x14tm3bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:space-line" {...props}></Icon>
