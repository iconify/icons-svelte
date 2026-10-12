<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1-o68t3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1-o68t3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:users-filled" {...props}></Icon>
