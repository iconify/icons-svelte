<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfzz9-bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cfzz9-bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:wordpress" {...props}></Icon>
