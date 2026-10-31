<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d81fbrxtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d81fbrxtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-j-filled" {...props}></Icon>
