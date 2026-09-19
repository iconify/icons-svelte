<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w95g0dfgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":488};
const content = `<path class="w95g0dfgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:spotify" {...props}></Icon>
