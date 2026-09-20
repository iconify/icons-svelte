<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2d9a-f-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d2d9a-f-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:trophy" {...props}></Icon>
