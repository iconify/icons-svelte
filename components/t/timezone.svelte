<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw8uhj0ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw8uhj0ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timezone" {...props}></Icon>
