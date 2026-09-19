<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td6uc1khz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":456};
const content = `<path class="td6uc1khz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:vimeo" {...props}></Icon>
