<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc-vnabro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sc-vnabro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-arrow-right-filled" {...props}></Icon>
