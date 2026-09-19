<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmhsfe4-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":488};
const content = `<path class="dmhsfe4-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:yahoo-buzz" {...props}></Icon>
