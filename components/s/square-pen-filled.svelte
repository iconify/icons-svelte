<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbma3xpbl.css';
import '../../css/a/avpyb3bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbma3xpbl"/><path class="avpyb3bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-pen-filled" {...props}></Icon>
