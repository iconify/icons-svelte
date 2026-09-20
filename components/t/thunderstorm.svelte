<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smepu6bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smepu6bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:thunderstorm" {...props}></Icon>
