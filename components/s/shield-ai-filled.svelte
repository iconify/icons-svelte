<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntws4y6ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntws4y6ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:shield-ai-filled" {...props}></Icon>
