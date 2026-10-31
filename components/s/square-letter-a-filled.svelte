<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ickn83b4x.css';
import '../../css/j/jpp-j2s8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ickn83b4x"/><path clip-rule="evenodd" class="jpp-j2s8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-a-filled" {...props}></Icon>
