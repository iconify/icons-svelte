<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ody0k2bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ody0k2bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:step-forward" {...props}></Icon>
