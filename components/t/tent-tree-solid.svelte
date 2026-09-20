<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1y5m5elh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1y5m5elh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tent-tree-solid" {...props}></Icon>
