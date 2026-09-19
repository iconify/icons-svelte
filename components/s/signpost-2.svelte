<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq_mpnbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fq_mpnbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:signpost-2" {...props}></Icon>
