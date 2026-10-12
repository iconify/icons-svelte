<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9y5vx-ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9y5vx-ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-chevron-right-filled" {...props}></Icon>
