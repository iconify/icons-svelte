<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zotrfkt_o.css';
import '../../css/f/fp8qfjbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zotrfkt_o"/><path clip-rule="evenodd" class="fp8qfjbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-b-filled" {...props}></Icon>
