<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epvlj5hbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epvlj5hbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:square-axis-dashed-vertical" {...props}></Icon>
