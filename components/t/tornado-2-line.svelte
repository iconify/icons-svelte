<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz8sj8b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz8sj8b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tornado-2-line" {...props}></Icon>
