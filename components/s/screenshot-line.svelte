<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsp84l_lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsp84l_lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:screenshot-line" {...props}></Icon>
