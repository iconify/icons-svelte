<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lljs6_q0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lljs6_q0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:star-half-filled" {...props}></Icon>
