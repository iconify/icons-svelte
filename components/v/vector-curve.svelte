<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvmbfl4zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvmbfl4zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-curve" {...props}></Icon>
