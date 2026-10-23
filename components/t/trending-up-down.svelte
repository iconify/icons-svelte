<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-qz8s0dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-qz8s0dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:trending-up-down" {...props}></Icon>
