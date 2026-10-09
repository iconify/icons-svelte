<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyb-4v94m.css';
import '../../css/o/olexncc0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xyb-4v94m"/><path class="olexncc0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-grid-20" {...props}></Icon>
