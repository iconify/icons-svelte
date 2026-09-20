<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvd31abxp.css';
import '../../css/c/cdofe-b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nvd31abxp"/><path class="cdofe-b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:spline-area-chart" {...props}></Icon>
