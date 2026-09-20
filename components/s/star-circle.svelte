<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tis7hb_9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tis7hb_9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-circle" {...props}></Icon>
