<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvaesh6dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvaesh6dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:slice" {...props}></Icon>
