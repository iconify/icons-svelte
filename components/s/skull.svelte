<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on59fzbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="on59fzbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:skull" {...props}></Icon>
