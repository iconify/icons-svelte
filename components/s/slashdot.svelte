<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5hl6bc3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":488};
const content = `<path class="j5hl6bc3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:slashdot" {...props}></Icon>
