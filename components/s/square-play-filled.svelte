<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpve2kbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kpve2kbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-play-filled" {...props}></Icon>
