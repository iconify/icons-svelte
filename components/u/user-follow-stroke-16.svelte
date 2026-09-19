<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo3soyo3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eo3soyo3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:user-follow-stroke-16" {...props}></Icon>
