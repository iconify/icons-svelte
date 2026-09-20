<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq7b6qb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq7b6qb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:slash-octagon" {...props}></Icon>
