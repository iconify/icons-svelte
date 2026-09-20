<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4i2n-v3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v4i2n-v3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tree-and-bench" {...props}></Icon>
