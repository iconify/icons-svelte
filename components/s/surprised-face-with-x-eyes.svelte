<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j87ilt-jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j87ilt-jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:surprised-face-with-x-eyes" {...props}></Icon>
