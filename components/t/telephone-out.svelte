<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl145g8bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl145g8bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:telephone-out" {...props}></Icon>
