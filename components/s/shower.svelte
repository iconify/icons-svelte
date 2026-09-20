<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se_7ygblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="se_7ygblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:shower" {...props}></Icon>
