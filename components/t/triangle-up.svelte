<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6t7b7boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="k6t7b7boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-up" {...props}></Icon>
