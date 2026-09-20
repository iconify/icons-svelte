<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdjsuka3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vdjsuka3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:storage-fermenter" {...props}></Icon>
