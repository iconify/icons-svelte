<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yml45ibji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yml45ibji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:server-remove" {...props}></Icon>
