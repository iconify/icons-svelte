<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdii07f6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":16};
const content = `<path class="qdii07f6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:tab" {...props}></Icon>
