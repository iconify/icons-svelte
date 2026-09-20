<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnhminbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnhminbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-polyline-remove" {...props}></Icon>
