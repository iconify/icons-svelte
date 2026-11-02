<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b167aabvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b167aabvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:train-4-line" {...props}></Icon>
