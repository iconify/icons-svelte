<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuexo0a4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zuexo0a4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:video" {...props}></Icon>
