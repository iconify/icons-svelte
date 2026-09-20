<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1mnnn-xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1mnnn-xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shining-2-line" {...props}></Icon>
