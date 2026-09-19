<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ils92p-0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ils92p-0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:smallcircle-circle" {...props}></Icon>
