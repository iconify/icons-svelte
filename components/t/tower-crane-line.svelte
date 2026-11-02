<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi4ud7b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi4ud7b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tower-crane-line" {...props}></Icon>
