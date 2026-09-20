<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa9p1mb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa9p1mb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:send-fill" {...props}></Icon>
