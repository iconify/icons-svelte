<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axv5cq26u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axv5cq26u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-line" {...props}></Icon>
