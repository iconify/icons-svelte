<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h39_wuqyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h39_wuqyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-off-outline" {...props}></Icon>
