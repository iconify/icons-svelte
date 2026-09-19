<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o--vv303e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":408};
const content = `<path class="o--vv303e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:shopping-basket" {...props}></Icon>
