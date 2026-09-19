<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gflo552_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gflo552_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:signpost-fill" {...props}></Icon>
