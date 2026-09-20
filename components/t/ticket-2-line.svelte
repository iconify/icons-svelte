<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6419mrrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6419mrrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ticket-2-line" {...props}></Icon>
