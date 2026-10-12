<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6c6j0kyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6c6j0kyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:scale-3d-filled" {...props}></Icon>
