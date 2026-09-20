<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn9-thbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn9-thbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sd-card-fill" {...props}></Icon>
