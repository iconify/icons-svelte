<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjy60jbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjy60jbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stacked-chart-fill" {...props}></Icon>
