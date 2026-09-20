<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb55eibow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pb55eibow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tree-palm" {...props}></Icon>
