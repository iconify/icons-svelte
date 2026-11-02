<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz5knnw1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz5knnw1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-2-fill" {...props}></Icon>
