<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq-njj5ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wq-njj5ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangle-left-with-plus" {...props}></Icon>
