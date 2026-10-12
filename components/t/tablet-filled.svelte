<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lebm5qx9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lebm5qx9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tablet-filled" {...props}></Icon>
