<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m00jcezkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m00jcezkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:virus-line" {...props}></Icon>
