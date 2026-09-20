<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9rz7-b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9rz7-b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-difference" {...props}></Icon>
