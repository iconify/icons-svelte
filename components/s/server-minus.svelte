<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuf3lcbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuf3lcbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:server-minus" {...props}></Icon>
