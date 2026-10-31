<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am3o8ac5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am3o8ac5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:slash" {...props}></Icon>
