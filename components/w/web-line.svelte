<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw3xk19cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw3xk19cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:web-line" {...props}></Icon>
