<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x12x9ab0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x12x9ab0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:settings-2-filled" {...props}></Icon>
