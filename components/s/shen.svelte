<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9lipul9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9lipul9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:shen" {...props}></Icon>
