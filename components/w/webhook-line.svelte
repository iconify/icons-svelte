<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exv8mvnqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exv8mvnqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:webhook-line" {...props}></Icon>
