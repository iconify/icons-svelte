<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-k55vb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-k55vb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:table-line" {...props}></Icon>
