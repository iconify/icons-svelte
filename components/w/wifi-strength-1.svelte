<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwi0_l9lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwi0_l9lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-1" {...props}></Icon>
