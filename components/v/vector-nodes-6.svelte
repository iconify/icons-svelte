<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5zq6fb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="i5zq6fb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:vector-nodes-6" {...props}></Icon>
