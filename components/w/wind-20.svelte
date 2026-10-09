<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq1h8k7oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dq1h8k7oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-20" {...props}></Icon>
