<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdz9vxb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":472};
const content = `<path class="bdz9vxb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:sound-plus" {...props}></Icon>
