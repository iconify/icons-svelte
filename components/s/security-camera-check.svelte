<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na6slrbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na6slrbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:security-camera-check" {...props}></Icon>
