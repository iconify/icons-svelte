<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4haf-2fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="t4haf-2fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:skeletonize" {...props}></Icon>
