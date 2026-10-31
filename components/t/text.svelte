<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc-o3ybut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc-o3ybut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:text" {...props}></Icon>
