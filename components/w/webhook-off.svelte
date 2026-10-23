<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se0258yit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se0258yit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:webhook-off" {...props}></Icon>
