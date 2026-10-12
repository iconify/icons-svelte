<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_x2r5e0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h_x2r5e0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-sigma-filled" {...props}></Icon>
