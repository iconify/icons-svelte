<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxl7f5q3q.css';
import '../../css/m/m-_748b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vxl7f5q3q"/><path clip-rule="evenodd" class="m-_748b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:text-editor-16" {...props}></Icon>
