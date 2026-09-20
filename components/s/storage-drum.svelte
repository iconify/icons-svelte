<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjs8q412m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zjs8q412m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:storage-drum" {...props}></Icon>
