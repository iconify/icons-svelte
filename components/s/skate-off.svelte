<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djz9cpvmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djz9cpvmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skate-off" {...props}></Icon>
