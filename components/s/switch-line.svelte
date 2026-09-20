<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq8l2sbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq8l2sbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:switch-line" {...props}></Icon>
