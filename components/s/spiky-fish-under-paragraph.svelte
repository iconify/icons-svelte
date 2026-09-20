<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_rqqg3ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b_rqqg3ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spiky-fish-under-paragraph" {...props}></Icon>
