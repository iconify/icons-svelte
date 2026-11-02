<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3k2p-2sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3k2p-2sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:time-fill" {...props}></Icon>
