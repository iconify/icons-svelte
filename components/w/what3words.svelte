<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twomk51ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twomk51ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:what3words" {...props}></Icon>
