<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmpz7gb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmpz7gb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ticket-confirmation" {...props}></Icon>
