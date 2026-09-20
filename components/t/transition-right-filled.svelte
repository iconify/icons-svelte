<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8x6g5o0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8x6g5o0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:transition-right-filled" {...props}></Icon>
