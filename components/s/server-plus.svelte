<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7tx827ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7tx827ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:server-plus" {...props}></Icon>
