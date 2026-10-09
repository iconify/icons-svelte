<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bohi61rzr.css';
import '../../css/v/v1gt_db3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bohi61rzr"/><path class="v1gt_db3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:torch-20-bold" {...props}></Icon>
