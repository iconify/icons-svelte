<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmebglb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmebglb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:send-to-back-filled" {...props}></Icon>
