<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr02l2t6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sr02l2t6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:video-stroke-16" {...props}></Icon>
