<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3c3bj8tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l3c3bj8tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:traffic-cone-and-question-mark" {...props}></Icon>
