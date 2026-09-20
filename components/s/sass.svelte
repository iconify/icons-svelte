<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-t_88bev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-t_88bev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sass" {...props}></Icon>
