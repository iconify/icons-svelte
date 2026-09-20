<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imy963b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imy963b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tailwind-css" {...props}></Icon>
