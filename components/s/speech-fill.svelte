<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug1e5o2al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug1e5o2al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:speech-fill" {...props}></Icon>
