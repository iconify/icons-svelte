<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws97a5ros.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws97a5ros"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:trousers" {...props}></Icon>
