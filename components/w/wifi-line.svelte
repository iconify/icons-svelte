<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhoo-skte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhoo-skte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wifi-line" {...props}></Icon>
