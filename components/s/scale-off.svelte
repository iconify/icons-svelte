<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co93ein0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co93ein0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:scale-off" {...props}></Icon>
