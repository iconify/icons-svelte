<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3lpxulyc.css';
import '../../css/i/i0ekbjbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3lpxulyc"/><path class="i0ekbjbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-arrow-left-enter-filled" {...props}></Icon>
