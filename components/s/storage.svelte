<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgvh4kkig.css';
import '../../css/r/r5sqe9b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pgvh4kkig"/><path class="r5sqe9b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:storage" {...props}></Icon>
