<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca4h09bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ca4h09bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:semi-trailer" {...props}></Icon>
