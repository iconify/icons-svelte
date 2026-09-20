<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq423_b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq423_b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ticket-3-filled" {...props}></Icon>
