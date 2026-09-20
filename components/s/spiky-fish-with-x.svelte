<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfdcb-bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jfdcb-bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spiky-fish-with-x" {...props}></Icon>
