<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/delwp5q_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="delwp5q_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wallet-2-fill" {...props}></Icon>
