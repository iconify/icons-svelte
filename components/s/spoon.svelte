<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xygj0f-en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xygj0f-en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spoon" {...props}></Icon>
