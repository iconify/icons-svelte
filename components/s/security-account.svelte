<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in3x3jgej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in3x3jgej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:security-account" {...props}></Icon>
