<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1cfb39vj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1cfb39vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:settings-5-line" {...props}></Icon>
