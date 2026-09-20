<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pby5r5c2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pby5r5c2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-2-line" {...props}></Icon>
