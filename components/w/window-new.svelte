<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvr2w2bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lvr2w2bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:window-new" {...props}></Icon>
