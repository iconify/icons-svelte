<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zho1v3d8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zho1v3d8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:turtle-fill" {...props}></Icon>
