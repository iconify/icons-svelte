<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkagiub5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkagiub5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-fill" {...props}></Icon>
