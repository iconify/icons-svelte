<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggj0uge_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggj0uge_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skip-off" {...props}></Icon>
