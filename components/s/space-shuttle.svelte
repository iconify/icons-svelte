<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_-p3bvlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2176,"height":1408};
const content = `<path class="j_-p3bvlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:space-shuttle" {...props}></Icon>
