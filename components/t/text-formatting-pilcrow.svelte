<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh7i6gbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eh7i6gbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-pilcrow" {...props}></Icon>
