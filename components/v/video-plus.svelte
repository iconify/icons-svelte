<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6a1je0ov.css';
import '../../css/l/lx1df9t7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6a1je0ov"/><path class="lx1df9t7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:video-plus" {...props}></Icon>
