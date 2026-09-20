<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j42fu2bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j42fu2bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:valve-closed" {...props}></Icon>
