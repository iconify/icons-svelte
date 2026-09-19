<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trt9y-blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":455,"height":512};
const content = `<path class="trt9y-blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:stylable" {...props}></Icon>
