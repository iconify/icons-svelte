<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze168ccux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ze168ccux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-blockquote" {...props}></Icon>
