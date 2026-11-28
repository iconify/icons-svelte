<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k41hbxyox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k41hbxyox primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sparkle-duotone" {...props}></Icon>
