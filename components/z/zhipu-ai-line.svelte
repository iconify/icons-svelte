<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfdwlufse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfdwlufse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:zhipu-ai-line" {...props}></Icon>
