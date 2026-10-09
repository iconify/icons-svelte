<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d97ksobub.css';
import '../../css/z/zepzk2bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d97ksobub"/><path class="zepzk2bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sunset-20" {...props}></Icon>
