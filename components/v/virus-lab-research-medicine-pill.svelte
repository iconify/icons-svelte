<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7t_42bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7t_42bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:virus-lab-research-medicine-pill" {...props}></Icon>
