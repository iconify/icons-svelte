<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw8fn3uor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw8fn3uor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:test-tube-off" {...props}></Icon>
