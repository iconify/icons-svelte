<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzdbhquoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xzdbhquoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shopping-bag" {...props}></Icon>
