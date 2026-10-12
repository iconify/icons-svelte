<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpve6yaul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpve6yaul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:signpost-filled" {...props}></Icon>
