<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esg4p2r4f.css';
import '../../css/d/dmxnto4mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esg4p2r4f"/><path class="dmxnto4mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:vibrate-off-filled" {...props}></Icon>
