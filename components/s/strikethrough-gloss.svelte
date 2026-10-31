<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by7fs_z4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by7fs_z4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:strikethrough-gloss" {...props}></Icon>
