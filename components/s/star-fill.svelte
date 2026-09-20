<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vczweh8xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vczweh8xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:star-fill" {...props}></Icon>
