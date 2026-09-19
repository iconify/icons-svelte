<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7zs_nueb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j7zs_nueb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:vimeo" {...props}></Icon>
