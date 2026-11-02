<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1vk-2blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1vk-2blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowflake-fill" {...props}></Icon>
