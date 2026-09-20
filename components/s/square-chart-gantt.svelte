<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scix5ob1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scix5ob1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:square-chart-gantt" {...props}></Icon>
