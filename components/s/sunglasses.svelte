<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdknls8fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdknls8fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sunglasses" {...props}></Icon>
