<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8hjgpb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="o8hjgpb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:view" {...props}></Icon>
