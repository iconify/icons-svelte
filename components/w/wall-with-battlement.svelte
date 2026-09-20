<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwhqzbc9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bwhqzbc9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wall-with-battlement" {...props}></Icon>
