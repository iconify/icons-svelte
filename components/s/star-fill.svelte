<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly-x4abvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly-x4abvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:star-fill" {...props}></Icon>
