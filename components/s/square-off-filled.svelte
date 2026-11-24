<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt_jtyb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt_jtyb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-off-filled" {...props}></Icon>
